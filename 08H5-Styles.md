# H5-Styles

## 目录

-   [章节摘要](#章节摘要)
-   [样式属性](#样式属性)
-   [背景颜色](#背景颜色)
-   [文本颜色](#文本颜色)
-   [字体](#字体)
-   [文本大小](#文本大小)
-   [文本对齐](#文本对齐)

# 章节摘要

-   Use the `style` attribute for styling HTML elements &#x20;

    使用 `style` 属性设置HTML元素的样式
-   Use `background-color` for background color &#x20;

    使用 `background-color` 作为背景色
-   Use `color` for text colors &#x20;

    使用 `color` 作为文本颜色
-   Use `font-family` for text fonts &#x20;

    对于文本字体使用 `font-family`
-   Use `font-size` for text sizes &#x20;

    使用 `font-size` 作为文本大小
-   Use `text-align` for text alignment &#x20;

    使用 `text-align` 进行文本对齐

# 样式属性

Setting the style of an HTML element, can be done with the `style` attribute.

设置HTML元素的样式可以通过 `style` 属性完成。

The HTML `style` attribute has the following syntax:

HTML `style` 属性具有以下语法：

```html
< tagname  style=" property : value; ">
```

The ***property*** is a CSS property. The ***value*** is a CSS value.

属性是CSS属性。该值是CSS值。

# 背景颜色

The CSS `background-color` property defines the background color for an HTML element.

CSS `background-color` 属性定义HTML元素的背景颜色。

Set the background color for a page to powderblue: &#x20;

将页面的背景色设置为粉蓝色：

```html
<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
```

Set background color for two different elements: &#x20;

为两个不同的元素设置背景颜色：

```html
<body>

<h1 style="background-color:powderblue;">This is a heading</h1>
<p style="background-color:tomato;">This is a paragraph.</p>

</body>
```

# 文本颜色

The CSS `color` property defines the text color for an HTML element:

CSS `color` 属性定义HTML元素的文本颜色：

```html
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>
```

# 字体

The CSS `font-family` property defines the font to be used for an HTML element:

CSS `font-family` 属性定义HTML元素使用的字体：

```html
<h1 style="font-family:verdana;">This is a heading</h1>
<p style="font-family:courier;">This is a paragraph.</p>
```

# 文本大小

The CSS `font-size` property defines the text size for an HTML element:

CSS `font-size` 属性定义HTML元素的文本大小：

```html
<h1 style="font-size:300%;">This is a heading</h1>
<p style="font-size:160%;">This is a paragraph.</p>
```

# 文本对齐

The CSS `text-align` property defines the horizontal text alignment for an HTML element:

CSS `text-align` 属性定义HTML元素的水平文本对齐方式：

```html
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:center;">Centered paragraph.</p>
```
