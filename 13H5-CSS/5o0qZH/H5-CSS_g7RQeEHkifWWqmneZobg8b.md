# H5-CSS

## 目录

-   [Chapter Summary](#Chapter-Summary)
-   [Using CSS ](#Using-CSS-)
-   [Inline CSS ](#Inline-CSS-)
-   [Internal CSS ](#Internal-CSS-)
-   [External CSS](#External-CSS)
-   [CSS Colors, Fonts and Sizes](#CSS-Colors-Fonts-and-Sizes)
-   [CSS Border](#CSS-Border)
-   [CSS Padding](#CSS-Padding)
-   [CSS Margin](#CSS-Margin)
-   [Link to External CSS](#Link-to-External-CSS)

> 📌HTML CSS

| Tag                                                                | Description                                                |
| ------------------------------------------------------------------ | ---------------------------------------------------------- |
| [\<style>](https://www.w3schools.com/tags/tag_style.asp "<style>") | Defines style information for an HTML document             |
| [\<link>](https://www.w3schools.com/tags/tag_link.asp "<link>")    | Defines a link between a document and an external resource |

# Chapter Summary

> 📌章节摘要

-   Use the HTML `style` attribute for inline styling &#x20;

    使用HTML `style` 属性进行内联样式设置
-   Use the HTML `<style>` element to define internal CSS &#x20;

    使用HTML `<style>` 元素定义内部CSS
-   Use the HTML `<link>` element to refer to an external CSS file &#x20;

    使用HTML `<link>` 元素引用外部CSS文件
-   Use the HTML `<head>` element to store \<style> and \<link> elements &#x20;

    使用HTML `<head>` 元素存储
-   Use the CSS `color` property for text colors &#x20;

    将CSS `color` 属性用于文本颜色
-   Use the CSS `font-family` property for text fonts &#x20;

    将CSS `font-family` 属性用于文本字体
-   Use the CSS `font-size` property for text sizes &#x20;

    使用CSS `font-size` 属性设置文本大小
-   Use the CSS `border` property for borders &#x20;

    为边框使用CSS `border` 属性
-   Use the CSS `padding` property for space inside the border &#x20;

    为边框内的空间使用CSS `padding` 属性
-   Use the CSS `margin` property for space outside the border &#x20;

    为边框外的空间使用CSS `margin` 属性

CSS stands for Cascading Style Sheets.

CSS代表级联样式表。

CSS saves a lot of work. It can control the layout of multiple web pages all at once.

CSS节省了很多工作。它可以同时控制多个网页的布局。

Cascading Style Sheets (CSS) is used to format the layout of a webpage. &#x20;

层叠样式表（CSS）用于格式化网页的布局。

With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more! &#x20;

使用CSS，您可以控制颜色，字体，文本大小，元素之间的间距，元素的位置和布局，使用什么背景图像或背景颜色，不同设备和屏幕大小的不同显示，等等！

> 📌**Tip:** The word **cascading** means that a style applied to a parent element will also apply to all children elements within the parent.提示：层叠这个词意味着应用于父元素的样式也将应用于父元素中的所有子元素。So, if you set the color of the body text to "blue", all headings, paragraphs, and other text elements within the body will also get the same color (unless you specify something else)!所以，如果你将正文的颜色设置为“蓝色”，正文中的所有标题、段落和其他文本元素也将得到相同的颜色（除非你指定了其他颜色）！

# `Using CSS `

> 📌使用CSS

CSS can be added to HTML documents in 3 ways:

CSS可以通过三种方式添加到HTML文档中：

Inline - by using the style attribute inside HTML elements

内联-通过在HTML元素中使用 style 属性

Internal - by using a \<style> element in the \<head> section

内部-通过在 \<head> 节中使用 \<style> 元素

External - by using a \<link> element to link to an external CSS file

External -通过使用 \<link> 元素链接到外部CSS文件

The most common way to add CSS, is to keep the styles in external CSS files. However, in this tutorial we will use inline and internal styles, because this is easier to demonstrate, and easier for you to try it yourself.

添加CSS的最常见方法是将样式保存在外部CSS文件中。然而，在本教程中，我们将使用内联和内部样式，因为这更容易演示，并且更容易让您自己尝试。

# `Inline CSS `

> 📌内联CSS

An inline CSS is used to apply a unique style to a single HTML element. &#x20;

内联CSS用于将独特的样式应用于单个HTML元素。

An inline CSS uses the `style` attribute of an HTML element.

内联CSS使用HTML元素的 `style` 属性。

The following example sets the text color of the `<h1>` element to blue, and the text color of the `<p>` element to red:

下面的示例将 `<h1>` 元素的文本颜色设置为蓝色，将 `<p>` 元素的文本颜色设置为红色：

```html
<h1 style="color:blue;">A Blue Heading</h1>

<p style="color:red;">A red paragraph.</p>
```

# `Internal CSS `

> 📌内部CSS

An internal CSS is used to define a style for a single HTML page. &#x20;

内部CSS用于为单个HTML页面定义样式。

An internal CSS is defined in the `<head>` section of an HTML page, within a `<style>` element.内

部CSS定义在HTML页面的 `<head>` 部分，在 `<style>` 元素中。

The following example sets the text color of ALL the `<h1>` elements (on that page) to blue, and the text color of ALL the `<p>` elements to red. In addition, the page will be displayed with a "powderblue" background color: 

下面的示例将该页面上所有 `<h1>` 元素的文本颜色设置为蓝色，将所有 `<p>` 元素的文本颜色设置为红色。此外，页面将以“粉蓝色”背景色显示：

```html
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

# `External CSS`

> 📌外部CSS

An external style sheet is used to define the style for many HTML pages. &#x20;

外部样式表用于定义许多HTML页面的样式。

To use an external style sheet, add a link to it in the `<head>` section of each HTML page:要使用外部

样式表，请在每个HTML页面的 `<head>` 部分添加指向该样式表的链接：

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

The external style sheet can be written in any text editor. The file must not contain any HTML code, and must be saved with a .css extension. &#x20;

外部样式表可以在任何文本编辑器中编写。该文件不能包含任何HTML代码，并且必须使用.css扩展名保存。

Here is what the "styles.css" file looks like: &#x20;

下面是“styles.css”文件的样子：

```html
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
```

> 📌**Tip:** With an external style sheet, you can change the look of an entire web site, by changing one file!提示：使用外部样式表，您可以通过更改一个文件来更改整个网站的外观！

# `CSS Colors, Fonts and Sizes`

> 📌颜色，字体，大小

Here, we will demonstrate some commonly used CSS properties. You will learn more about them later. &#x20;

在这里，我们将演示一些常用的CSS属性。稍后您将了解更多有关它们的信息。

The CSS `color` property defines the text color to be used.CSS&#x20;

`color` 属性定义要使用的文本颜色。

The CSS `font-family` property defines the font to be used.CSS&#x20;

`font-family` 属性定义要使用的字体。

The CSS `font-size` property defines the text size to be used.CSS&#x20;

`font-size` 属性定义要使用的文本大小。

```html
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  color: blue;
  font-family: verdana;
  font-size: 300%;
}
p {
  color: red;
  font-family: courier;
  font-size: 160%;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

# `CSS Border`

> 📌CSS边框

The CSS `border` property defines a border around an HTML element.CSS&#x20;

`border` 属性定义了HTML元素的边框。

> 📌**Tip:** You can define a border for nearly all HTML elements.提示：你可以为几乎所有的HTML元素定义边框。

```html
p {
  border: 2px solid powderblue;
}
```

# `CSS Padding`

> 📌CSS内边距

The CSS `padding` property defines a padding (space) between the text and the border.CSS&#x20;

`padding` 属性定义了文本和边框之间的填充（空格）。

```html
p {
  border: 2px solid powderblue;
  padding: 30px;
}
```

# `CSS Margin`

> 📌使用CSS外边距

The CSS margin property defines a margin (space) outside the border.

CSS margin 属性定义边框外的边距（空格）。

```html
p {
  border: 2px solid powderblue;
  margin: 50px;
}
```

# Link to External CSS

> 📌使用CSS外部样式

External style sheets can be referenced with a full URL or with a path relative to the current web page. &#x20;

外部样式表可以使用完整的URL或相对于当前网页的路径进行引用。

This example uses a full URL to link to a style sheet: &#x20;

此示例使用完整URL链接到样式表：

```html
<link rel="stylesheet" href=" https://www.w3schools.com/html/styles.css ">
```

This example links to a style sheet located in the html folder on the current web site:  &#x20;

此示例链接到位于当前网站的html文件夹中的样式表：

```html
<link rel="stylesheet" href="/html/styles.css">
```

This example links to a style sheet located in the same folder as the current page: &#x20;

此示例链接到与当前页位于同一文件夹中的样式表：

```html
<link rel="stylesheet" href="styles.css">
```
