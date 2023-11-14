# H5-Basic&#x20;

## 目录

-   [HTML文档](#HTML文档)
-   [HTML声明](#HTML声明)
-   [HTML标题](#HTML标题)
-   [HTML段落](#HTML段落)
-   [HTML链接](#HTML链接)
-   [HTML图像](#HTML图像)
    -   [如何查看 HTML 源代码](#如何查看-HTML-源代码)
    -   [查看 HTML 源代码：](#查看-HTML-源代码)
-   [检查HTML元素](#检查HTML元素)
-   [code](#code)
-   [代码高亮库](#代码高亮库)

# HTML文档

All HTML documents must start with a document type declaration: \<!DOCTYPE html>.

所有HTML文档必须以文档类型声明开头：第0号。

The HTML document itself begins with \<html> and ends with \</html>.

HTML文档本身以 \<html> 开始，以 \</html> 结束。

The visible part of the HTML document is between \<body> and \</body>.

HTML文档的可见部分在 \<body> 和 \</body> 之间。

```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

# HTML声明

The `<!DOCTYPE>` declaration represents the document type, and helps browsers to display web pages correctly.

`<!DOCTYPE>` 声明表示文档类型，帮助浏览器正确显示网页。

It must only appear once, at the top of the page (before any HTML tags). &#x20;

它只能出现一次，在页面顶部（在任何HTML标记之前）。

The `<!DOCTYPE>` declaration is not case sensitive.

`<!DOCTYPE>` 声明不区分大小写。

The `<!DOCTYPE>` declaration for HTML5 is:

HTML5的 `<!DOCTYPE>` 声明是：

```html
<!DOCTYPE html>
```

# HTML标题

HTML headings are defined with the \<h1> to \<h6> tags.

HTML标题由 \<h1> 到 \<h6> 标签定义。

\<h1> defines the most important heading. \<h6> defines the least important heading:&#x20;

\<h1> 定义了最重要的标题。 \<h6> 定义了最不重要的标题：

```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
```

# HTML段落

HTML paragraphs are defined with the `<p>` tag:

HTML段落使用 `<p>` 标签定义：

```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

# HTML链接

HTML links are defined with the `<a>` tag:

HTML链接使用 `<a>` 标签定义：

```html
<a href="https://www.w3schools.com">This is a link</a>
```

The link's destination is specified in the href attribute.&#x20;

链接的目的地在 href 属性中指定。

Attributes are used to provide additional information about HTML elements.

属性用于提供有关HTML元素的附加信息。

You will learn more about attributes in a later chapter.

您将在后面的章节中了解有关属性的更多信息。

# HTML图像

HTML images are defined with the `<img>` tag.

HTML图像使用 `<img>` 标签定义。

The source file (`src`), alternative text (`alt`), `width`, and `height` are provided as attributes:

源文件（ `src` ）、替代文本（ `alt` ）、 `width` 和 `height` 作为属性提供：

```html
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```

## 如何查看 HTML 源代码

Have you ever seen a Web page and wondered "Hey! How did they do that?"

你有没有看过一个网页，想知道“嘿！他们是怎么做到的？

## 查看 HTML 源代码：

Right-click in an HTML page and select "View Page Source" (in Chrome) or "View Source" (in Edge), or similar in other browsers. This will open a window containing the HTML source code of the page.

在HTML页面中单击鼠标右键，然后选择“查看页面源代码”（在Chrome中）或“查看源代码”（在Edge中），或在其他浏览器中选择类似选项。这将打开一个包含页面HTML源代码的窗口。

# 检查HTML元素

Right-click on an element (or a blank area), and choose "Inspect" or "Inspect Element" to see what elements are made up of (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles panel that opens.

右键单击元素（或空白区域），然后选择“检查”或“检查元素”以查看元素的组成（您将看到HTML和CSS）。您还可以在打开的“元素”或“样式”面板中动态编辑HTML或CSS。

# code

`<code>`标签用于表示行内的计算机代码或编程代码片段，并在文本中以等宽字体显示。

以下是`<code>`标签的几个使用案例：

1.  演示行内代码：可以使用`<code>`标签来演示行内的代码或命令。

    示例：
    ```javascript
    在终端中运行以下命令：<code>npm install</code>
    ```
    结果：

    在终端中运行以下命令：`npm install`
2.  显示代码片段：可以使用`<code>`标签将一段代码片段以等宽字体显示。

    示例：
    ```html
    <code>
      function sayHello(name) {
        console.log('Hello, ' + name + '!');
      }
    </code>
    ```
    结果：
    ```javascript
    function sayHello(name) {
      console.log('Hello, ' + name + '!');
    }
    ```
3.  内联代码注释：在文档中进行代码注释时，可以使用`<code>`标签来表示注释的代码部分。

    示例：
    ```html
    通过修改 <code>font-size</code> 属性来调整文本大小。
    ```
    结果：

    通过修改 `font-size` 属性来调整文本大小。

注意，`<code>`标签仅用于格式化纯文本代码。如果要显示语法高亮的代码块或更复杂的代码展示，应该使用HTML中专门用于代码的元素，如`<pre>`和`<code>`的组合或第三方代码高亮库。

# 代码高亮库

有许多第三方代码高亮库可用于在网页中实现代码高亮效果。以下是几个常用的代码高亮库：

1.  `Prism.js`：Prism.js 是一个轻量级且强大的代码语法高亮库，支持多种编程语言。它易于使用，并提供了丰富的主题和插件。
2.  `Highlight.js`：Highlight.js 是一个功能丰富的代码高亮库，支持大量的编程语言和模板引擎。它易于使用，支持自动检测代码语言，并提供了多种主题可供选择。
3.  `CodeMirror`：CodeMirror 是一个功能强大的文本编辑器库，同时也支持代码高亮。它提供了完整的编辑器功能，并支持超过 100 种编程语言和风格。
4.  `Prettify`：Prettify 是 Google 推出的一款简单易用的代码高亮库。它支持多种编程语言，通过简单的配置即可实现代码高亮。
5.  `Rainbow.js`：Rainbow\.js 是一个轻量级的代码语法高亮库，支持多种编程语言。它具有简洁的界面和易于使用的 API，适用于简单的代码高亮需求。
