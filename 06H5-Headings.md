# H5-Headings

## 目录

-   [HTML标题](#HTML标题)
-   [标题很重要](#标题很重要)
-   [较大标题](#较大标题)

| Tag                                                                        | Description                          |
| -------------------------------------------------------------------------- | ------------------------------------ |
| [\<html>](https://www.w3schools.com/tags/tag_html.asp "<html>")            | Defines the root of an HTML document |
| [\<body>](https://www.w3schools.com/tags/tag_body.asp "<body>")            | Defines the document's body          |
| [\<h1> to \<h6>](https://www.w3schools.com/tags/tag_hn.asp "<h1> to <h6>") | Defines HTML headings                |

# HTML标题

HTML headings are titles or subtitles that you want to display on a webpage.

HTML标题是要在网页上显示的标题或副标题。

HTML headings are defined with the `<h1>` to `<h6>` tags.

HTML标题由 `<h1>` 到 `<h6>` 标签定义。

`<h1>` defines the most important heading. `<h6>` defines the least important heading.

`<h1>` 定义了最重要的标题。 `<h6>` 定义了最不重要的标题。

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

> 📌**Note:** Browsers automatically add some white space (a margin) before and after a heading.注意：浏览器会自动在标题前后添加一些白色（页边距）。

# 标题很重要

Search engines use the headings to index the structure and content of your web pages. &#x20;

搜索引擎使用标题来索引网页的结构和内容。

Users often skim a page by its headings. It is important to use headings to show the document structure. &#x20;

用户通常通过标题浏览网页。使用标题来显示文档结构是很重要的。

`<h1>` headings should be used for main headings, followed by `<h2>` headings, then the less important `<h3>`, and so on.

`<h1>` 标题应该用于主标题，然后是 `<h2>` 标题，然后是不太重要的 `<h3>` ，依此类推。

> 📌**Note:** Use HTML headings for headings only. Don't use headings to make text **BIG** or **bold**.注意：仅对标题使用HTML标题。不要使用标题使文本变大或加粗。

# 较大标题

Each HTML heading has a default size. However, you can specify the size for any heading with the `style` attribute, using the CSS `font-size` property:

每个HTML标题都有一个默认大小。但是，您可以使用CSS `font-size` 属性为任何具有 `style` 属性的标题指定大小：

```html
<h1 style="font-size:60px;">Heading 1</h1>
```
