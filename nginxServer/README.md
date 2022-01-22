# Sooooo difficult to setup (; _ ;)
    damn
## Centos 7
> PHP install part
```
yum --enablerepo=remi-php74 install php
                                        #php-fpm etc.
```
###### Some code copied form [atrandys](https://github.com/atrandys/wordpress/blob/master/wp_install.sh)
```
wget https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
wget https://rpms.remirepo.net/enterprise/remi-release-7.rpm
rpm -Uvh remi-release-7.rpm epel-release-latest-7.noarch.rpm --force --nodeps
#sed -i "0,/enabled=0/s//enabled=1/" /etc/yum.repos.d/epel.repo
yum -y install  unzip vim tcl expect curl socat
yum -y install php74 php74-php-gd php74-php-opcache php74-php-pdo php74-php-mbstring php74-php-cli php74-php-fpm php74-php-mysqlnd php74-php-xml
service php74-php-fpm start
chkconfig php74-php-fpm on
```
> NginX install part
```
wget http://nginx.org/download/nginx-1.20.2.tar.gz
tar zxf nginx-1.20.2.tar.gz
./configure --prefix=/usr --with-stream
make && make install
```
