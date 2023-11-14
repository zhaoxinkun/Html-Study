# H5-Attributes

## 目录

-   [章节摘要](#章节摘要)
-   [HTML](#HTML)
-   [href](#href)
-   [src](#src)
-   [width/height](#widthheight)
-   [alt](#alt)
-   [style](#style)
-   [lang](#lang)
-   [title ](#title-)
-   [We Suggest: Always Use Lowercase Attributes](#We-Suggest-Always-Use-Lowercase-Attributes)
-   [We Suggest: Always Quote Attribute Values](#We-Suggest-Always-Quote-Attribute-Values)
    -   [Good](#Good)
    -   [Bad](#Bad)
-   [单引号还是双引号？](#单引号还是双引号)

| Attributes   |        |
| ------------ | ------ |
| href         | 链接外部资源 |
| src          | 文件地址   |
| width/height | 宽度/高度  |
| alt          | 加载失败说明 |
| style        | 样式     |
| lang         | 语言类型   |
| title        | 标题     |

# 章节摘要

-   All HTML elements can have **attributes** &#x20;

    所有HTML元素都可以有属性
-   The `href` attribute of `<a>` specifies the URL of the page the link goes to &#x20;

    `<a>` 的 `href` 属性指定链接指向的页面的URL
-   The `src` attribute of `<img>` specifies the path to the image to be displayed &#x20;

    `<img>` 的 `src` 属性指定要显示的图像的路径
-   The `width` and `height` attributes of `<img>` provide size information for images &#x20;

    `<img>` 的 `width` 和 `height` 属性提供图像的大小信息
-   The `alt` attribute of `<img>` provides an alternate text for an image &#x20;

    `<img>` 的 `alt` 属性为图像提供替代文本
-   The `style` attribute is used to add styles to an element, such as color, font, size, and more &#x20;

    `style` 属性用于为元素添加样式，如颜色、字体、大小等
-   The `lang` attribute of the `<html>` tag declares the language of the Web page &#x20;

    `<html>` 标记的 `lang` 属性声明了Web页面的语言
-   The `title` attribute defines some extra information about an element &#x20;

    `title` 属性定义了一些关于元素的额外信息

# `HTML`

-   All HTML elements can have **attributes** &#x20;

    所有HTML元素都可以有属性
-   Attributes provide **additional information** about elements &#x20;

    属性提供有关元素的附加信息
-   Attributes are always specified in **the start tag** &#x20;

    属性始终在开始标记中指定
-   Attributes usually come in name/value pairs like: **name="value"** &#x20;

    属性通常以名称/值对形式出现，如：name=“value”

# `href`

The `<a>` tag defines a hyperlink. The `href` attribute specifies the URL of the page the link goes to:

`<a>` 标签定义了一个超链接。 `href` 属性指定链接指向的页面的URL：

```html
<a href="https://www.w3schools.com">Visit W3Schools</a>

```

# `src`

The `<img>` tag is used to embed an image in an HTML page. The `src` attribute specifies the path to the image to be displayed:

`<img>` 标签用于在HTML页面中嵌入图像。 `src` 属性指定要显示的图像的路径：

```html
<img src="img_girl.jpg">
```

There are two ways to specify the URL in the `src` attribute:

在 `src` 属性中指定URL有两种方式：

**1. Absolute URL** - Links to an external image that is hosted on another website. Example: src="[https://www.w3schools.com/images/img\_girl.jpg](https://www.w3schools.com/images/img_girl.jpg "https://www.w3schools.com/images/img_girl.jpg")".

1.绝对URL -指向托管在其他网站上的外部图像的链接。示例：src=”[https://www.w3schools.com/images/img\_girl.jpg“。](https://www.w3schools.com/images/img_girl.jpg“。 "https://www.w3schools.com/images/img_girl.jpg“。")

> 📌**Notes:** External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

注：外部图像可能受版权保护。如果您没有获得许可使用它，您可能会违反版权法。此外，你不能控制外部图像;它可以突然被移除或改变。

**2. Relative URL** - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img\_girl.jpg". If the URL begins with a slash, it will be relative to the domain.

2.相对URL -指向网站中托管的图像的链接。这里，URL不包括域名。如果URL开头没有斜杠，则它将相对于当前页面。示例：src=“img\_girl.jpg”。如果URL以斜杠开头，则它将是相对于域的。Example: src="/images/img\_girl.jpg".示例：src="/images/img\_girl.jpg”。

**Tip:** It is almost always best to use relative URLs. They will not break if you change domain.

提示：使用相对URL几乎总是最好的。如果你改变域，它们不会断开。

# `width/height`

The `<img>` tag should also contain the `width` and `height` attributes, which specify the width and height of the image (in pixels):

`<img>` 标签还应该包含 `width` 和 `height` 属性，它们指定图像的宽度和高度（以像素为单位）：

```html
<img src="img_girl.jpg" width="500" height="600">

```

# `alt`

The required `alt` attribute for the `<img>` tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the `src` attribute, or if the user uses a screen reader.

如果图像由于某种原因无法显示，则 `<img>` 标记所需的 `alt` 属性指定图像的替代文本。这可能是由于连接速度慢，或 `src` 属性中的错误，或者用户使用屏幕阅读器。

```html
<img src="img_girl.jpg" alt="Girl with a jacket">
```

See what happens if we try to display an image that does not exist:

看看如果我们尝试显示不存在的图像会发生什么：

```html
<img src="img_typo.jpg" alt="Girl with a jacket">
```

# `style`

The `style` attribute is used to add styles to an element, such as color, font, size, and more.

`style` 属性用于为元素添加样式，如颜色、字体、大小等。

```html
<p style="color:red;">This is a red paragraph.</p>
```

# `lang`

You should always include the `lang` attribute inside the `<html>` tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

您应该始终在 `<html>` 标记中包含 `lang` 属性，以声明Web页面的语言。这是为了帮助搜索引擎和浏览器。

The following example specifies English as the language:

下面的示例指定英语作为语言：

```html
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
```

Country codes can also be added to the language code in the `lang` attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.

国家代码也可以添加到 `lang` 属性中的语言代码中。因此，前两个字符定义了HTML页面的语言，最后两个字符定义了国家。

The following example specifies English as the language and United States as the country:

以下示例指定英语作为语言，美国作为国家/地区：

```html
<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>
```

# `title`&#x20;

The `title` attribute defines some extra information about an element.

`title` 属性定义了关于元素的一些额外信息。

The value of the title attribute will be displayed as a tooltip when you mouse over the element:

将鼠标移到元素上时，title属性的值将显示为工具提示：

```html
<p title="I'm a tooltip">This is a paragraph.</p>
```

# `We Suggest: Always Use Lowercase Attributes`

> 📌我们建议：始终使用小写属性

The HTML standard does not require lowercase attribute names.

HTML标准不要求属性名称小写。

The title attribute (and all other attributes) can be written with uppercase or lowercase like title or TITLE.

title属性（以及所有其他属性）可以用大写或小写书写，如title或TITLE。

However, W3C recommends lowercase attributes in HTML, and demands lowercase attributes for stricter document types like XHTML.

然而，W3C建议在HTML中使用小写属性，并要求更严格的文档类型（如XHTML）使用小写属性。

> At W3Schools we always use lowercase attribute names.

在W3Schools，我们总是使用小写的属性名。

# `We Suggest: Always Quote Attribute Values`

> 📌我们建议：始终引用属性值

The HTML standard does not require quotes around attribute values. &#x20;

HTML标准不要求属性值用引号括起来。

However, W3C **recommends** quotes in HTML, and **demands** quotes for stricter document types like XHTML.

然而，W3C建议在HTML中使用引号，并要求在更严格的文档类型（如XHTML）中使用引号。

## Good

```html
<a href=" https://www.w3schools.com/html/ ">Visit our HTML tutorial</a>
```

## Bad

```html
<a href=https://www.w3schools.com/html/>Visit our HTML tutorial</a>
```

Sometimes you have to use quotes. This example will not display the title attribute correctly, because it contains a space:

有时你必须使用引号。此示例将无法正确显示title属性，因为它包含空格：

```html
<p title=About W3Schools>
```

> &#x20;At W3Schools we always use quotes around attribute values.

在W3Schools，我们总是在属性值周围使用引号。

# 单引号还是双引号？

Double quotes around attribute values are the most common in HTML, but single quotes can also be used. &#x20;

属性值的双引号在HTML中最常见，但也可以使用单引号。

In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes: &#x20;

在某些情况下，当属性值本身包含双引号时，有必要使用单引号：

```html
<p title='John "ShotGun" Nelson'>

```

Or vice versa反之亦然

```html
<p title="John 'ShotGun' Nelson">
```
