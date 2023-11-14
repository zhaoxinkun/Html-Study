# The Pciture Element

## 目录

-   [\<picture> Element  ](#picture-Element--)
-   [When to use the Picture Element  ](#When-to-use-the-Picture-Element--)
    -   [1. Bandwidth ](#1-Bandwidth-)
    -   [2. Format Support ](#2-Format-Support-)

The HTML `<picture>` element allows you to display different pictures for different devices or screen sizes.

HTML `<picture>` 元素允许您为不同的设备或屏幕大小显示不同的图片。

![](image/image_D6cx8QmFI3.png)

# `<picture> Element  `

> 📌HTML图片元素

The HTML `<picture>` element gives web developers more flexibility in specifying image resources.

HTML `<picture>` 元素为Web开发人员提供了更大的灵活性来指定图像资源。

The `<picture>` element contains one or more `<source>` elements, each referring to different images through the `srcset` attribute. This way the browser can choose the image that best fits the current view and/or device.

`<picture>` 元素包含一个或多个 `<source>` 元素，每个元素通过 `srcset` 属性引用不同的图像。这样，浏览器可以选择最适合当前视图和/或设备的图像。

Each `<source>` element has a `media` attribute that defines when the image is the most suitable.

每个 `<source>` 元素都有一个 `media` 属性，定义了图像何时最合适。

Show different images for different screen sizes: &#x20;

为不同的屏幕尺寸显示不同的图像：

```html
<picture>
  <source media="(min-width: 650px)" srcset="img_food.jpg">
  <source media="(min-width: 465px)" srcset="img_car.jpg">
  <img src="img_girl.jpg">
</picture>
```

> 📌**Note:** Always specify an `<img>` element as the last child element of the `<picture>` element. The `<img>` element is used by browsers that do not support the `<picture>` element, or if none of the `<source>` tags match.注意：始终指定 `<img>` 元素作为 `<picture>` 元素的最后一个子元素。 `<img>` 元素由不支持 `<picture>` 元素的浏览器使用，或者如果没有 `<source>` 标签匹配。

# `When to use the Picture Element  `

> 📌何时使用Picture Element

There are two main purposes for the `<picture>` element:`<picture>` 元素有两个主要用途：

## `1. Bandwidth `

带宽

If you have a small screen or device, it is not necessary to load a large image file. The browser will use the first `<source>` element with matching attribute values, and ignore any of the following elements.如果您的屏幕或设备较小，则无需加载较大的图像文件。浏览器将使用具有匹配属性值的第一个 `<source>` 元素，并忽略以下任何元素。

## `2. Format Support `

格式支持

Some browsers or devices may not support all image formats. By using the `<picture>` element, you can add images of all formats, and the browser will use the first format it recognizes, and ignore any of the following elements.某些浏览器或设备可能不支持所有图像格式。通过使用 `<picture>` 元素，您可以添加所有格式的图像，浏览器将使用它识别的第一种格式，并忽略以下任何元素。

> 📌**Note:** The browser will use the first `<source>` element with matching attribute values, and ignore any following `<source>` elements.注意：浏览器将使用第一个具有匹配属性值的 `<source>` 元素，并忽略任何后续的 `<source>` 元素。
