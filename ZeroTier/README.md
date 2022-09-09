# ZeroTier Setup Guide
> I've planned to try other methods to have a high bandwidth vLan environment, check [here](https://github.com/MaBoCoMark/MaBoCo/blob/master/ZeroTier/PendingMethods.md).
## Operating System
[Windows](https://github.com/MaBoCoMark/MaBoCo/blob/master/ZeroTier/README.md#windows) / [MacOS](https://github.com/MaBoCoMark/MaBoCo/blob/master/ZeroTier/README.md#macos) / [Linux](https://github.com/MaBoCoMark/MaBoCo/blob/master/ZeroTier/README.md#linux)
### Windows
> To allow incoming streams (Ping etc.)

Win + R : **secpol.msc**

Then **"网络列表管理器策略"**

Done! :D

###### another way to set:
Run PowerShell(Admin), then type:

> Get-NetConnectionProfile

and you will see

```
InterfaceIndex : %aRandomNumber%
```
then type:

> Set-NetConnectionProfile -InterfaceIndex %aRandomNumber% -NetworkCategory Private

Done :D

### MacOS
> Everything is allowed on MacOS by default
> so you have nothing to configure xD
### Linux
> Probably use Linux for SuperNode only...

```
TOKEN=$(sudo cat /var/lib/zerotier-one/authtoken.secret)
```
```
NODEID=$(zerotier-cli info | cut -d " " -f 3)
```
```
NWID=977b5e7acd65be2b
```
```
curl "http://localhost:9993/controller/network/${NWID}/member" -H "X-ZT1-AUTH: ${TOKEN}" 
```
ZeroTier official instruction [link](https://docs.zerotier.com/self-hosting/network-controllers)

