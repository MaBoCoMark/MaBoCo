# Github Flavoured Markdown Syntax
<table width="100%">
	<tr>
		<th colspan="4">Basic</th>
	</tr>
	<tr>
		<td><a href="#headings">Headings</a></td>
		<td><a href="#text-styles">Text Styles</a></td>
		<td><a href="#quoting">Quoting</a></td>
		<td><a href="#links">Links</a></td>
	</tr>
  	<tr>
		<td><a href="#images">Images</a></td>
		<td><a href="#lists">Lists</a></td>
		<td><a href="#checkboxes">Checkboxes</a></td>
		<td><a href="#mentions">Mentions</a></td>
	</tr>
  	<tr>
		<td><a href="#emoji">Emoji</a></td>
		<td><a href="#footnotes">Footnotes</a></td>
		<td><a href="#comments">Comments</a></td>
		<td><a href="#raw-rendering">Raw Rendering</a></td>
	</tr>
	<tr>
		<td colspan="4" align="center"><b>Advanced</b></td>
	</tr>
	<tr>
		<td><a href="#tables">Tables</a></td>
		<td><a href="#collapsed-sections">Collapsed Sections</a></td>
		<td><a href="#code-blocks">Code Blocks</a></td>
		<td><a href="#diagrams">Diagrams</a></td>
	</tr>
	<tr>
		<td><a href="#latex-expressions">LaTeX expressions</a></td>
		<td><a href="#horizontal-breaklines">Horizontal Breaklines</a></td>
		<td><a href="#nested-elements">Nested Elements</a></td>
		<td><a href="#html-usage">HTML usage</a></td>
	</tr>
	<tr>
		<td colspan="4" align="center"><a href="#references"><b>References</b></a></td>
	</tr>
	
</table>

## Headings
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>
<table><tr><th>Style</th><th>Syntax</th><th>Example</th><th>Appearance</th></tr><tr><td>first-level heading<br>(has breakline)</td><td><code>#</code></td><td><code># H1</code></td><td><h1>First-level Heading</h1></td></tr><tr><td>second-level heading<br>(has breakline)</td><td><code>##</code></td><td><code>## H2</code></td><td><h2>Second-level Heading</h2></td></tr><tr><td>third-level heading</td><td><code>###</code></td><td><code>### H3</code></td><td><h3>Third-level Heading</h3></td></tr><tr><td>fourth-level heading</td><td><code>####</code></td><td><code>#### H4</code></td><td><h4>First-level Heading</h4></td></tr><tr><td>fifth-level heading</td><td><code>#####</code></td><td><code>##### H5</code></td><td><h5>Fifth-level Heading</h5></td></tr><tr><td>sixth-level heading</td><td><code>######</code></td><td><code>###### H6</code></td><td><h6>Sixth-level Heading</h6></td></tr></table>

## Text Styles
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>
<table><thead><tr><th>Style</th><th>Syntax</th><th>Keyboard shortcut</th><th>Example</th><th>Output</th></tr></thead><tbody><tr><td>Bold</td><td><code>** **</code> or<code>__ __</code></td><td><kbd>Command</kbd>+<kbd>B</kbd> (Mac) or<kbd>Ctrl</kbd>+<kbd>B</kbd> (Windows/Linux)</td><td><code>**This is bold text**</code></td><td><strong>This is bold text</strong></td></tr><tr><td>Italic</td><td><code>* *</code> or<code>_ _</code> &emsp;&emsp;&emsp;&emsp;</td><td><kbd>Command</kbd>+<kbd>I</kbd> (Mac) or<kbd>Ctrl</kbd>+<kbd>I</kbd> (Windows/Linux)</td><td><code>*This text is italicized*</code></td><td><em>This text is italicized</em></td></tr><tr><td>Strikethrough</td><td><code>~~ ~~</code></td><td></td><td><code>~~This was mistaken text~~</code></td><td><del>This was mistaken text</del></td></tr><tr><td>Bold and nested italic</td><td><code>** **</code> and<code>_ _</code></td><td></td><td><code>**This text is _extremely_ important**</code></td><td><strong>This text is<em>extremely</em> important</strong></td></tr><tr><td>All bold and italic</td><td><code>*** ***</code></td><td></td><td><code>***All this text is important***</code></td><td><strong><em>All this text is important</em></strong></td></tr><tr><td>Subscript</td><td><code>&lt;sub&gt; &lt;/sub&gt;</code></td><td></td><td><code>&lt;sub&gt;sub&lt;/sub&gt;Script</code></td><td><sub>sub</sub>Script</td></tr><tr><td>Superscript</td><td><code>&lt;sup&gt; &lt;/sup&gt;</code></td><td></td><td><code>&lt;sup&gt;sup&lt;/sup&gt;Scrpit</code></td><td><sup>sup</sup>Script</td></tr></tbody></table>

## Quoting
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>
<table><tr><th>Style</th><th>Syntax</th><th>Example</th><th>Output</th></tr><tr><td>Full line</td><td><code>></code></td><td><code>> a line of quoting text</code></td><td><blockquote><p>a line of quoting text</p></blockquote></td></tr><tr><td>Part text</td><td><code>` `</code></td><td><code>quote `part` text</code></td><td><p>quote<code>part</code> text</p></td></tr><tr><td>Codeblock</td><td><code>```</code></td>
<td><table><tr><td><pre><code>```
placeholder
```</code></pre></td></tr></table></td><td><table><tr><td><pre><code>bruh</code></pre></td></tr></table></td></tr><tr><td>Highlighted Codeblock</td><td><code>```language</code></td><td><pre>
<code>```swift
let static_bool = false;
previous.getSuffix();
```</code></pre></td><td><p><a target="_blank" rel="noopener noreferrer" href="https://github.com/MaBoCoMark/MaBoCo/raw/master/MarkDown/Swift_Codeblock_example.png"><img src="https://github.com/MaBoCoMark/MaBoCo/raw/master/MarkDown/Swift_Codeblock_example.png" alt="" style="max-width: 100%;"></a></p></td></tr><tr><td>Key</td><td><code>&lt;kbd&gt;</code></td><td><code>&lt;kbd&gt;cmd&lt;/kbd&gt;+1</code></td><td><kbd>cmd</kbd>+1</td></tr></table>


## Links
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>
<table><tr><th>Style</th><th>Syntax</th><th>Example</th><th>Output</th></tr><tr><td>Link</td><td><code>[]()</code></td><td><code>Click [Here](#link)</code></td><td>Click <a href="#links">Here</a></td></tr><tr><td colspan="4" align="center"><strong>Advanced Usages check </strong><a href="https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/autolinked-references-and-urls"><strong>Here</strong></a></td></tr></table>

## Images
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>
<table><tr><th>Style</th><th>Syntax</th><th>Example</th><th>Output</th></tr><tr><td>Image<br>(no description)</td><td><code>![]()</code></td><td><code>![](https://avatars.githubusercontent.com/u/9919?s=200&v=4)</code></td><td><a ><img src="https://avatars.githubusercontent.com/u/9919?s=200&v=4" alt="GitHub Avatar"></a></td></tr><tr><td>Image<br>(with description)</td><td><code>![description]()</code></td><td><code>![Powered By Shields.io](https://img.shields.io/badge/Markdown-Image%20Example-9cf?style=for-the-badge&logo=GitHub&labelColor=333)</code></td><td><a><img src="https://camo.githubusercontent.com/8543feedf918595518f2503b83f42b8b7ba1903e5fd070d395cea1c7e871c969/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d61726b646f776e2d496d6167652532304578616d706c652d3963663f7374796c653d666f722d7468652d6261646765266c6f676f3d476974487562266c6162656c436f6c6f723d333333" alt="Powered By Shields.io" data-canonical-src="https://img.shields.io/badge/Markdown-Image%20Example-9cf?style=for-the-badge&amp;logo=GitHub&amp;labelColor=333" style="max-width: 100%;"></a></td></tr></table>

   - To specify the theme an image is shown to

     ```HTML
     <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
        <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
        <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
     </picture>
     ```

## Lists
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>
<table><tr><th>Style</th><th>Syntax</th><th>Example</th><th>Output</th></tr><tr><td>UNordered List</td><td><code>-</code> /<code>*</code> /<code>+</code></td><td><pre><code>- item 1
* item 2
+ item 3</code></pre></td><td><ul><li>item 1</li></ul><ul><li>item 2</li></ul><ul><li>item 3</li></ul></td></tr><tr><td>Ordered List</td><td><code>number.</code></td><td><pre><code>1. item 1
2. item 2
3. item 3</code></pre></td><td><ol><li>item 1</li><li>item 2</li><li>item 3</li></ol></td></tr><tr><td rowspan="2">Nested Lists</td><td rowspan="2">Use<kbd>␣</kbd> to align<br><br>number of spaces<br>are depends on<br>the text above<br><br>You may check<br><kbd>↑</kbd> on the left</td><td><pre><code>1. Layer 1
   - Layer 2
     - Layer 3</code></pre></td><td><ol><li>Layer 1<ul><li>Layer 2<ul><li>Layer 3</li></ul></li></ul></li></ol></td></tr><tr><td><pre><code>100. Layer 1
␣␣␣␣␣↑␣Layer 2
␣␣␣␣␣␣␣↑ Layer 3</code></pre></td><td><ol start="100"><li>Layer 1<ul><li>Layer 2<ul><li>Layer 3</li></ul></li></ul></li></ol></td></tr></table>

## Checkboxes
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>
<table><tr><th>Style</th><th>Syntax</th><th>Example</th><th>Output</th></tr><tr><td>Un-Checked</td><td><code>- [ ]</code></td><td><code>- [ ] Empty Box</code></td><td><ul><li>[ ] Empty Box</li></ul></td></tr><tr><td>Checked</td><td><code>- [x]</code></td><td><code>- [x] Checked Box</code></td><td><ul><li>[x] Checked Box</li></ul></td></tr>
<!-- <tr><td>Box with description</td><td><code>- [ ] \(description)</code></td><td><code>- [ ] \(optional)</code></td><td><ul><li>[ ] (optional)</li></ul></td></tr>  -->
<tr><td colspan="4" align="center"><img src="https://github.com/MaBoCoMark/MaBoCo/raw/master/MarkDown/Advanced_Todo_List.png"><br>For more information, see "<a href="https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-task-lists">About task lists</a>."</td></tr></table>

## Mentions
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>

## Emoji
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>

## Footnotes
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>

## Comments
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>

## Raw Rendering
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>

## Tables
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>

## Collapsed Sections
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>

## Code Blocks
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>

## Diagrams
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>

## LaTeX expressions
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>

## Horizontal Breaklines
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>

## Nested Elements
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>

## HTML usage
<table><tr><th><a href="#Github-Flavoured-Markdown-Syntax"><b>Back to top</b></a></th></tr></table>

_ _ _
###### References
