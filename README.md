#HTML学习拾贝

HTML comments
----
Comment tags `<!--` and `-->` are used to insert comments in HTML.
Comments are not displayed by the browser, but they can help document your HTML.
With comments you can place notifications and reminders in your HTML:

<!-- Write your comments here -->

HTML Links
----
###HTML Links - Hyperlinks
Links are found in nearly all web pages. Links allow users to click their way from page to page.
HTML links are hyperlinks.
A hyperlink is a text or an image you can click on, and jump to another document.

In HTML, links are defined with the `<a>` tag:

```
<a href="url">link text</a>
```

- Demo  of HTML Links  

`<a href="http://www.w3schools.com/html/">Visit W3 HTML tutorial</a>`

<a href="http://www.w3schools.com/html/">Visit W3 HTML tutorial</a>

###Local Links
The example above used an absolute URL (A full web address).
A local link (link to the same web site) is specified with a relative URL (without `http://www....`).

```HTML
<a id="id">anchor</a>
<a href="#id">Jump to the anchor </a> 
```

####HTML Links - Create a Bookmark
HTML bookmarks are used to allow readers to jump to specific parts of a Web page.
Bookmarks are practical if your website has long pages.
To make a bookmark, you must first create the bookmark with the `id` attribute, and then add a link to it refering by id using `#`.
When the link is clicked, the page will scroll to the location with the bookmark.

- Demo  of Local Links  

`<a href="#end">Jump to the end</a>`  

 <a href="#end">Jump to the end</a>  

`<a id="local-links">local links anchor</a>`

 <a id="local-links">local links anchor</a>

###HTML Links - Image as Link
It is common to use images as links:




###Chapter Summary
- Use the HTML `<a>` element to define a link  
- Use the HTML **`href`** attribute to define the link address  
- Use the HTML **`target`** attribute to define where to open the linked document  
- Use the HTML `<img>` element (inside `<a>`) to use an image as a link  
- Use the HTML **`id`** attribute (id="value") to define bookmarks in a page  
- Use the HTML **`href`** attribute (href="#value") to link to the bookmark  

HTML Headings
----
Headings are defined with the `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading. `<h6>` defines the least important heading.

HTML				| Markdown
-----------------|--------------------------------------------------------------
`<h1>`				| #（===）
`<h2>`				| ##（---）
`<h3>`				| ###
`<h4>`				| ####
`<h5>`				| #####
`<h6>`				| ######

HTML text format
----
###强调文本`<em>`

###重要文本`<strong>`

###突出显示文本`<mark>`

###改变字号
####加大字号`<big>`

####减小字号`<small>`

###脚标
####上脚标`<sup>`

####下脚标`<sub>`

###下划线`<u>`

###删除线`<del>`

HTML layout
----
###水平线`<hr>`
###换行`<br>`
###段落`<p>`
###分区节`<div>`
####红色的标题
###对齐（align属性）

HTML Quotation and Citation Elements
----

Tag					| Description
-----------------|--------------------------------------------------------------
`<abbr>`			| Defines an abbreviation or acronym
`<address>` 		| Defines contact information for the author/owner of a document
`<bdo>` 			| Defines the text direction
`<blockquote>`	| Defines a section that is quoted from another source
`<cite>`			| Defines the title of a work
`<q>`				| Defines a short inline quotation

###1 作品标题cite

###2 短引用q

###3 块引用blockquote

###4 代码块
####41 代码块code
####42 代码块pre



`<a id="end">the end anchor</a>`

<a id="end">the end anchor</a>

`<a href="#local-links">Jump to local links</a>`

<a href="#local-links">Jump to local links</a>