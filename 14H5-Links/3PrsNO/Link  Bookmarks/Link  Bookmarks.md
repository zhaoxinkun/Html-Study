# Link  Bookmarks

## 目录

-   [Chapter Summary ](#Chapter-Summary-)
-   [Create a Bookmark in HTML](#Create-a-Bookmark-in-HTML)

> 📌锚点链接

# Chapter Summary&#x20;

> 📌章节摘要

-   Use the `id` attribute (id="*value*") to define bookmarks in a page &#x20;

    使用 `id` 属性（id=“value”）定义页面中的书签
-   Use the `href` attribute (href="#*value*") to link to the bookmark &#x20;

    使用 `href` 属性（href="#value”）链接到书签

HTML links can be used to create bookmarks, so that readers can jump to specific parts of a web page. &#x20;

HTML链接可用于创建书签，以便读者可以跳到网页的特定部分。

# `Create a Bookmark in HTML`

> 📌在HTML中创建书签

Bookmarks can be useful if a web page is very long. &#x20;

如果网页很长，书签可能很有用。

To create a bookmark - first create the bookmark, then add a link to it. &#x20;

要创建书签-首先创建书签，然后添加链接到书签。

When the link is clicked, the page will scroll down or up to the location with the bookmark. &#x20;

单击链接后，页面将向下或向上滚动到书签所在的位置。

First, use the `id` attribute to create a bookmark:

首先，使用 `id` 属性创建一个书签：

```html
<h2 id="C4">Chapter 4</h2>
```

Then, add a link to the bookmark ("Jump to Chapter 4"), from within the same page: &#x20;

然后，添加一个链接到书签（“跳转到第4章”），从同一页：

```html
<a href="#C4">Jump to Chapter 4</a>
```

You can also add a link to a bookmark on another page:

您也可以在另一个页面上添加书签的链接：

```html
<a href="html_demo.html#C4">Jump to Chapter 4</a>
```
