# Link

## 目录

-   [Chapter Summary](#Chapter-Summary)
-   [标签](#标签)
-   [区别](#区别)
-   [Hyperlinks](#Hyperlinks)
-   [Syntax](#Syntax)
-   [The target Attribute](#The-target-Attribute)
-   [Absolute URLs vs. Relative URLs](#Absolute-URLs-vs-Relative-URLs)
-   [Use an Image as a Link](#Use-an-Image-as-a-Link)
-   [Link to an Email Address](#Link-to-an-Email-Address)
-   [Link to Tel](#Link-to-Tel)
-   [Button as a Link](#Button-as-a-Link)
-   [Link Titles](#Link-Titles)
-   [More on Absolute URLs and Relative URLs](#More-on-Absolute-URLs-and-Relative-URLs)

> 📌HTML链接

|         |        |
| ------- | ------ |
| \<a>    | 超链接    |
| target  | 目标属性   |
| \<img>  | 图片     |
| mailto： | 链接到邮箱  |
| tel:    | 链接到手机  |
| button  | 按钮作为链接 |

# Chapter Summary

> 📌章节摘要

-   Use the `<a>` element to define a link &#x20;

    使用 `<a>` 元素定义链接
-   Use the `href` attribute to define the link address &#x20;

    使用 `href` 属性定义链接地址
-   Use the `target` attribute to define where to open the linked document &#x20;

    使用 `target` 属性定义打开链接文档的位置
-   Use the `<img>` element (inside `<a>`) to use an image as a link &#x20;

    使用 `<img>` 元素（在 `<a>` 内）将图像用作链接
-   Use the `mailto:` scheme inside the `href` attribute to create a link that opens the user's email program &#x20;

    使用 `href` 属性中的 `mailto:` 方案创建一个链接，用于打开用户的电子邮件程序

# 标签

-   `<a>`：用于创建超链接，指向其他网页或资源。
-   `<link>`：用于引入外部样式表或其他外部资源。

# 区别

`<a>` 标签和 `<link>` 标签在 HTML 中有不同的用途和功能。

1.  `<a>` 标签（锚点）:
    -   用于创建超链接，将一个文档与另一个文档或特定位置进行关联。
    -   `href` 属性指定链接目标的URL。
    -   `target`：指定链接将在何处打开，例如" \_blank"会在新窗口或新标签页中打开链接；
    -   `rel`：指定与链接目标的关系，例如" rel="nofollow" 可以告诉搜索引擎不要追踪此链接。
    -   用户点击链接时，可以跳转到指定的URL或页面。
    -   示例：
        ```html
        <a href="https://example.com" target="_blank" rel="nofollow">点击这里</a>
        ```
2.  `<link>` 标签:
    -   用于在 HTML 文档中引入外部资源，如样式表、图标等。
    -   `href`：指定要链接的外部资源的URL；
    -   `rel` 属性指定链接类型，常见的包括 stylesheet（样式表）和 icon（图标）。
    -   `href` 属性指定链接资源的URL。
    -   通常位于 `<head>` 标签内。
    -   示例：
        ```html
        <link rel="stylesheet" href="styles.css" type="text/css">
        ```

所以总结一下：

> 📌`<a>` 标签用于创建超链接，用于在文档之间进行导航;`<link>` 标签用于引入外部资源，如样式表、图标等。需要注意的是，`<a>` 标签也可以通过设置 `target` 属性来控制链接打开的方式（在当前窗口或新窗口打开）。而 `<link>` 标签没有类似的功能，它仅用于引入外部资源。

Links are found in nearly all web pages. Links allow users to click their way from page to page.

几乎所有的网页都有链接。链接允许用户从一个页面点击到另一个页面。

# `Hyperlinks`

> 📌超链接

HTML links are hyperlinks. &#x20;

HTML链接是超链接。

You can click on a link and jump to another document. &#x20;

您可以单击链接并跳转到另一个文档。

When you move the mouse over a link, the mouse arrow will turn into a little hand. &#x20;

当你把鼠标移到一个链接上时，鼠标箭头会变成一只小手。

> 📌**Note:** A link does not have to be text. A link can be an image or any other HTML element!注意：链接不一定是文本。链接可以是图像或任何其他HTML元素！

# `Syntax`

> 📌链接语法

The HTML `<a>` tag defines a hyperlink. It has the following syntax:

HTML `<a>` 标签定义了一个超链接。它具有以下语法：

```html
<a href=" url "> link text </a>
```

The most important attribute of the `<a>` element is the `href` attribute, which indicates the link's destination.

`<a>` 元素最重要的属性是 `href` 属性，它指示链接的目的地。

The *link text* is the part that will be visible to the reader.

链接文本是读者可见的部分。

Clicking on the link text, will send the reader to the specified URL address. &#x20;

点击链接文本，将读者发送到指定的URL地址。

This example shows how to create a link to [W3Schools.com](http://W3Schools.com "W3Schools.com"):

此示例说明如何创建指向W3Schools.com的链接：

```html
<a href=" https://www.w3schools.com/ ">Visit  W3Schools.com !</a>
```

By default, links will appear as follows in all browsers: &#x20;

默认情况下，链接将在所有浏览器中显示如下：

-   An unvisited link is underlined and blue &#x20;

    未访问的链接会用下划线和蓝色
-   A visited link is underlined and purple &#x20;

    访问过的链接带有下划线和紫色
-   An active link is underlined and red &#x20;

    活动链接带有下划线和红色

> 📌**Tip:** Links can of course be styled with CSS, to get another look!提示：链接当然可以用CSS来设计，以获得另一种外观！

# `The target Attribute`

> 📌目标属性

By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link. &#x20;

默认情况下，链接的页面将显示在当前浏览器窗口中。要更改此设置，必须为链接指定另一个目标。

The `target` attribute specifies where to open the linked document.

`target` 属性指定打开链接文档的位置。

The `target` attribute can have one of the following values:

`target` 属性可以具有以下值之一：

-   `_self` - Default. Opens the document in the same window/tab as it was clicked &#x20;

    `_self` -默认值。在单击文档的同一窗口/选项卡中打开文档
-   `_blank` - Opens the document in a new window or tab &#x20;

    `_blank` -在新窗口或选项卡中打开文档
-   `_parent` - Opens the document in the parent frame &#x20;

    `_parent` -在父框架中打开文档
-   `_top` - Opens the document in the full body of the window &#x20;

    `_top` -在窗口的全文中打开文档

Use target="\_blank" to open the linked document in a new browser window or tab: &#x20;

使用target="\_blank”在新的浏览器窗口或选项卡中打开链接的文档：

```html
<a href=" https://www.w3schools.com/ " target="_blank">Visit W3Schools!</a>
```

# `Absolute URLs vs. Relative URLs`

> 📌绝对URL和相对URL

Both examples above are using an **absolute URL** (a full web address) in the `href` attribute.

上面的两个示例都在 `href` 属性中使用了绝对URL（完整的网址）。

A local link (a link to a page within the same website) is specified with a **relative URL** (without the "[https://www](https://www "https://www")" part):

本地链接（指向同一网站内的页面的链接）使用相对URL指定（没有“https：//www”部分）：

```html
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>
```

# `Use an Image as a Link`

> 📌用图片作为链接

To use an image as a link, just put the `<img>` tag inside the `<a>` tag:

要使用图像作为链接，只需将 `<img>` 标记放在 `<a>` 标记内：

```html
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
```

# `Link to an Email Address`

> 📌链接向邮箱地址

Use `mailto:` inside the `href` attribute to create a link that opens the user's email program (to let them send a new email):

在 `href` 属性中使用 `mailto:` 创建一个链接，打开用户的电子邮件程序（让他们发送新电子邮件）：

```html
<a href="mailto:someone@example.com">Send email</a>
```

# `Link to Tel`

> 📌链接向手机号

# `Button as a Link`

> 📌按钮作为链接

To use an HTML button as a link, you have to add some JavaScript code. &#x20;

要使用HTML按钮作为链接，您必须添加一些JavaScript代码。

JavaScript allows you to specify what happens at certain events, such as a click of a button: &#x20;

JavaScript允许您指定在某些事件发生时发生的事情，例如单击按钮：

```html
<button onclick="document.location='default.asp'">HTML Tutorial</button>
```

> 📌**Tip:** Learn more about JavaScript in our [JavaScript Tutorial](https://www.w3schools.com/js/default.asp "JavaScript Tutorial").提示：在我们的JavaScript教程中了解更多关于JavaScript的信息。

# `Link Titles`

> 📌链接标题

The `title` attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.

`title` 属性指定关于元素的额外信息。当鼠标移到元素上时，这些信息通常显示为工具提示文本。

```html
<a href=" https://www.w3schools.com/html/ " title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>
```

# `More on Absolute URLs and Relative URLs`

> 📌更多关于绝对URL和相对URL

Use a full URL to link to a web page:  &#x20;

使用完整URL链接到网页：

```html
<a href=" https://www.w3schools.com/html/default.asp ">HTML tutorial</a>
```

Link to a page located in the html folder on the current web site:  &#x20;

链接到位于当前网站的html文件夹中的页面：

```html
<a href="default.asp">HTML tutorial</a>
```

> 📌You can read more about file paths in the chapter [HTML File Paths](https://www.w3schools.com/html/html_filepaths.asp "HTML File Paths").您可以在HTML文件路径一章中阅读有关文件路径的更多信息。
