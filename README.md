# ml_research_2025
for machine learning
<!DOCTYPE html>
<html>
<head>
<title>mark_down_cheet_sheet.md</title>
<meta http-equiv="Content-type" content="text/html;charset=UTF-8">

<style>
/* https://github.com/microsoft/vscode/blob/master/extensions/markdown-language-features/media/markdown.css */
/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

body {
	font-family: var(--vscode-markdown-font-family, -apple-system, BlinkMacSystemFont, "Segoe WPC", "Segoe UI", "Ubuntu", "Droid Sans", sans-serif);
	font-size: var(--vscode-markdown-font-size, 14px);
	padding: 0 26px;
	line-height: var(--vscode-markdown-line-height, 22px);
	word-wrap: break-word;
}

#code-csp-warning {
	position: fixed;
	top: 0;
	right: 0;
	color: white;
	margin: 16px;
	text-align: center;
	font-size: 12px;
	font-family: sans-serif;
	background-color:#444444;
	cursor: pointer;
	padding: 6px;
	box-shadow: 1px 1px 1px rgba(0,0,0,.25);
}

#code-csp-warning:hover {
	text-decoration: none;
	background-color:#007acc;
	box-shadow: 2px 2px 2px rgba(0,0,0,.25);
}

body.scrollBeyondLastLine {
	margin-bottom: calc(100vh - 22px);
}

body.showEditorSelection .code-line {
	position: relative;
}

body.showEditorSelection .code-active-line:before,
body.showEditorSelection .code-line:hover:before {
	content: "";
	display: block;
	position: absolute;
	top: 0;
	left: -12px;
	height: 100%;
}

body.showEditorSelection li.code-active-line:before,
body.showEditorSelection li.code-line:hover:before {
	left: -30px;
}

.vscode-light.showEditorSelection .code-active-line:before {
	border-left: 3px solid rgba(0, 0, 0, 0.15);
}

.vscode-light.showEditorSelection .code-line:hover:before {
	border-left: 3px solid rgba(0, 0, 0, 0.40);
}

.vscode-light.showEditorSelection .code-line .code-line:hover:before {
	border-left: none;
}

.vscode-dark.showEditorSelection .code-active-line:before {
	border-left: 3px solid rgba(255, 255, 255, 0.4);
}

.vscode-dark.showEditorSelection .code-line:hover:before {
	border-left: 3px solid rgba(255, 255, 255, 0.60);
}

.vscode-dark.showEditorSelection .code-line .code-line:hover:before {
	border-left: none;
}

.vscode-high-contrast.showEditorSelection .code-active-line:before {
	border-left: 3px solid rgba(255, 160, 0, 0.7);
}

.vscode-high-contrast.showEditorSelection .code-line:hover:before {
	border-left: 3px solid rgba(255, 160, 0, 1);
}

.vscode-high-contrast.showEditorSelection .code-line .code-line:hover:before {
	border-left: none;
}

img {
	max-width: 100%;
	max-height: 100%;
}

a {
	text-decoration: none;
}

a:hover {
	text-decoration: underline;
}

a:focus,
input:focus,
select:focus,
textarea:focus {
	outline: 1px solid -webkit-focus-ring-color;
	outline-offset: -1px;
}

hr {
	border: 0;
	height: 2px;
	border-bottom: 2px solid;
}

h1 {
	padding-bottom: 0.3em;
	line-height: 1.2;
	border-bottom-width: 1px;
	border-bottom-style: solid;
}

h1, h2, h3 {
	font-weight: normal;
}

table {
	border-collapse: collapse;
}

table > thead > tr > th {
	text-align: left;
	border-bottom: 1px solid;
}

table > thead > tr > th,
table > thead > tr > td,
table > tbody > tr > th,
table > tbody > tr > td {
	padding: 5px 10px;
}

table > tbody > tr + tr > td {
	border-top: 1px solid;
}

blockquote {
	margin: 0 7px 0 5px;
	padding: 0 16px 0 10px;
	border-left-width: 5px;
	border-left-style: solid;
}

code {
	font-family: Menlo, Monaco, Consolas, "Droid Sans Mono", "Courier New", monospace, "Droid Sans Fallback";
	font-size: 1em;
	line-height: 1.357em;
}

body.wordWrap pre {
	white-space: pre-wrap;
}

pre:not(.hljs),
pre.hljs code > div {
	padding: 16px;
	border-radius: 3px;
	overflow: auto;
}

pre code {
	color: var(--vscode-editor-foreground);
	tab-size: 4;
}

/** Theming */

.vscode-light pre {
	background-color: rgba(220, 220, 220, 0.4);
}

.vscode-dark pre {
	background-color: rgba(10, 10, 10, 0.4);
}

.vscode-high-contrast pre {
	background-color: rgb(0, 0, 0);
}

.vscode-high-contrast h1 {
	border-color: rgb(0, 0, 0);
}

.vscode-light table > thead > tr > th {
	border-color: rgba(0, 0, 0, 0.69);
}

.vscode-dark table > thead > tr > th {
	border-color: rgba(255, 255, 255, 0.69);
}

.vscode-light h1,
.vscode-light hr,
.vscode-light table > tbody > tr + tr > td {
	border-color: rgba(0, 0, 0, 0.18);
}

.vscode-dark h1,
.vscode-dark hr,
.vscode-dark table > tbody > tr + tr > td {
	border-color: rgba(255, 255, 255, 0.18);
}

</style>

<style>
/* Tomorrow Theme */
/* http://jmblog.github.com/color-themes-for-google-code-highlightjs */
/* Original theme - https://github.com/chriskempson/tomorrow-theme */

/* Tomorrow Comment */
.hljs-comment,
.hljs-quote {
	color: #8e908c;
}

/* Tomorrow Red */
.hljs-variable,
.hljs-template-variable,
.hljs-tag,
.hljs-name,
.hljs-selector-id,
.hljs-selector-class,
.hljs-regexp,
.hljs-deletion {
	color: #c82829;
}

/* Tomorrow Orange */
.hljs-number,
.hljs-built_in,
.hljs-builtin-name,
.hljs-literal,
.hljs-type,
.hljs-params,
.hljs-meta,
.hljs-link {
	color: #f5871f;
}

/* Tomorrow Yellow */
.hljs-attribute {
	color: #eab700;
}

/* Tomorrow Green */
.hljs-string,
.hljs-symbol,
.hljs-bullet,
.hljs-addition {
	color: #718c00;
}

/* Tomorrow Blue */
.hljs-title,
.hljs-section {
	color: #4271ae;
}

/* Tomorrow Purple */
.hljs-keyword,
.hljs-selector-tag {
	color: #8959a8;
}

.hljs {
	display: block;
	overflow-x: auto;
	color: #4d4d4c;
	padding: 0.5em;
}

.hljs-emphasis {
	font-style: italic;
}

.hljs-strong {
	font-weight: bold;
}
</style>

<style>
/*
 * Markdown PDF CSS
 */

 body {
	font-family: -apple-system, BlinkMacSystemFont, "Segoe WPC", "Segoe UI", "Ubuntu", "Droid Sans", sans-serif, "Meiryo";
	padding: 0 12px;
}

pre {
	background-color: #f8f8f8;
	border: 1px solid #cccccc;
	border-radius: 3px;
	overflow-x: auto;
	white-space: pre-wrap;
	overflow-wrap: break-word;
}

pre:not(.hljs) {
	padding: 23px;
	line-height: 19px;
}

blockquote {
	background: rgba(127, 127, 127, 0.1);
	border-color: rgba(0, 122, 204, 0.5);
}

.emoji {
	height: 1.4em;
}

code {
	font-size: 14px;
	line-height: 19px;
}

/* for inline code */
:not(pre):not(.hljs) > code {
	color: #C9AE75; /* Change the old color so it seems less like an error */
	font-size: inherit;
}

/* Page Break : use <div class="page"/> to insert page break
-------------------------------------------------------- */
.page {
	page-break-after: always;
}

</style>

<script src="https://unpkg.com/mermaid/dist/mermaid.min.js"></script>
</head>
<body>
  <script>
    mermaid.initialize({
      startOnLoad: true,
      theme: document.body.classList.contains('vscode-dark') || document.body.classList.contains('vscode-high-contrast')
          ? 'dark'
          : 'default'
    });
  </script>
<h1 id="1-headings">1. Headings</h1>
<p>How to give headings in markdown file?</p>
<h1 id="heading-1">Heading 1</h1>
<h2 id="heading-2">Heading 2</h2>
<h3 id="heading-3">Heading 3</h3>
<h4 id="heading-4">Heading 4</h4>
<h1 id="2-block-of-words">2. Block of words</h1>
<p>This is a normal text in markdown</p>
<blockquote>
<p>This is a block of specia; text</p>
<p>This is another block of special text</p>
</blockquote>
<h1 id="3-line-break">3. Line break</h1>
<blockquote>
<p>This is a normal text in markdown. \ n This is another line of text.
this can be the fimes . \ and this happend noramlly</p>
</blockquote>
<h1 id="4-bold-and-italic-text">4. Bold and Italic text</h1>
<blockquote>
<p>This is a normal text in markdown. \ n This is another line of text.</p>
<h1 id="heading-1-italic"><em>Heading</em> 1 italic</h1>
<h1 id="heading-2-bold"><strong>Heading</strong> 2 bold</h1>
<h1 id="heading-3-bold-and-italic"><em><strong>Heading</strong></em> 3 bold and italic</h1>
</blockquote>
<h1 id="5-bullet-and--lists">5 bullet and / lists</h1>
<h1 id="using--or--for-bullet-list">using * or + for bullet list</h1>
<ul>
<li>item 1</li>
<li>Islam
<ul>
<li>item 3</li>
</ul>
<ul>
<li>Islam</li>
<li></li>
</ul>
<em>islamabad</em> for italaic</li>
</ul>
<ul>
<li>DAy-1</li>
<li>day-2</li>
<li>day-3
<ul>
<li>sub day-1</li>
<li>sub day-2</li>
</ul>
</li>
</ul>
<h1 id="6-line-break-or-page-break">6 line break or page break</h1>
<p>this is afnan python class eay to learn.</p>
<hr>
<h2 id="this-can-also-be-done-by-space">this can also be done by space</h2>
<p>and this can also be done by&quot;*&quot;.</p>
<hr>
<p>and ythis can also be done by underscore</p>
<hr>
<ol start="8">
<li>
<h1 id="links-and-hyperlinks-to-be-saved">links and hyperlinks to be saved</h1>
<p>for hyperlinek you can create by&quot;&lt;&gt;&quot;
<a href="https://www.youtube.com/watch?v=qJqAXjz-Rh4&amp;list=PL9XvIvvVL50Fba7psesg6ynQXdipw-yoN&amp;index=11">https://www.youtube.com/watch?v=qJqAXjz-Rh4&amp;list=PL9XvIvvVL50Fba7psesg6ynQXdipw-yoN&amp;index=11</a>
for link you can create by&quot;()&quot;
<a href="https://www.youtube.com/watch?v=qJqAXjz-Rh4">link</a> braces after it immediately we paste link<br>
for link you can create by&quot;[]&quot;
[link](https://www.youtube.com/watch?v=qJqAXjz-Rh4)</p>
<p><a href="https://www.youtube.com/watch?v=qJqAXjz-Rh4&amp;list=PL9XvIvvVL50Fba7psesg6ynQXdipw-yoN&amp;index=12">the playlist of with quraan is here</a> tis is the way to create lines written by me as alink to be directed</p>
<p>similarly it can be done by writing for example in baces</p>
</li>
</ol>
<p>you see above without parathesie bracket</p>
<blockquote>
<p>lectures is <a href="https://www.youtube.com/watch?v=hJzhyQeGSt4">codanics</a></p>
<p>lecture is <a href="https://www.saas.gov.uk/">here</a></p>
</blockquote>
<h1 id="9-images-and-figures-with-links">9. images and figures with links</h1>
<p>to join this couse you can visit this QR code here :
<a href="qr.png">QR</a></p>
<p>and if write in this way it will show in the same file of preview <img src="qr.png" alt="QR"></p>
<p><img src="https://i0.wp.com/www.businessadvantagepng.com/wp-content/uploads/2019/06/Tuke_KaylaReimann.png?ssl=1" alt="pic"></p>
<p>[pdf][social media agility and customer engeemnt.pdf]</p>
<h1 id="10-adding-code-or-code-block">10. adding code or code block</h1>
<p>to print a string use this code <code>print(&quot;codanics&quot;)</code>  within text ,this is bcak comma at the corner of key board</p>
<p><code>print(&quot;Heloo  afnan &quot;)</code></p>
<p>bbut for multiple line use this code</p>
<pre class="hljs"><code><div>x=3+4
y=4+5
z=x+y
print(z)



</div></code></pre>
<p>This colur shows according to pyhton</p>
<pre class="hljs"><code><div>x=<span class="hljs-number">3</span>+<span class="hljs-number">4</span>
y=<span class="hljs-number">4</span>+<span class="hljs-number">5</span>
z=x+y
print(z)



</div></code></pre>
<pre class="hljs"><code><div>x=<span class="hljs-number">3</span>+<span class="hljs-number">4</span>
y=<span class="hljs-number">4</span>+<span class="hljs-number">5</span>
z=x+y
print(z)



</div></code></pre>
<pre class="hljs"><code><div>x=3+4
y=4+5
z=x+y
print(z)



</div></code></pre>
<h1 id="11-adding-tables">11. Adding Tables</h1>
<table>
<thead>
<tr>
<th style="text-align:left">Left Align</th>
<th style="text-align:center">Center Align</th>
<th style="text-align:right">Right Align</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left">Apple</td>
<td style="text-align:center">Orange</td>
<td style="text-align:right">100</td>
</tr>
<tr>
<td style="text-align:left">Banana</td>
<td style="text-align:center">Mango</td>
<td style="text-align:right">200</td>
</tr>
<tr>
<td style="text-align:left">Cherry</td>
<td style="text-align:center">Grapes</td>
<td style="text-align:right">300</td>
</tr>
</tbody>
</table>
<h1 id="12-content">12. Content</h1>
<p><a href="#1-headings">1.Heading</a><br>
<a href="#heading-2">2.Heading</a><br>
<a href="#heading-3">3.Heading</a><br>
<a href="#4-bold-and-italic-text">4-bold-and-italic-text</a></p>
<h1 id="13-install-extension">13. Install extension</h1>
<p>Sample text
<a href="https://www.youtube.com/watch?v=qJqAXjz-Rh4&amp;list=PL9XvIvvVL50Fba7psesg6ynQXdipw-yoN&amp;index=12">link</a></p>
<p><a href="qr.png">image</a></p>

</body>
</html>
