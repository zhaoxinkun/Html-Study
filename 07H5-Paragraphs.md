# H5-Paragraphs

## 目录

-   [HTML段落](#HTML段落)
-   [HTML显示](#HTML显示)
-   [HTML水平规则](#HTML水平规则)
-   [HTML换行符](#HTML换行符)
-   [诗歌问题](#诗歌问题)
-   [解决方案](#解决方案)

| Tag                                                          | Description                              |
| ------------------------------------------------------------ | ---------------------------------------- |
| [\<p>](https://www.w3schools.com/tags/tag_p.asp "<p>")       | Defines a paragraph                      |
| [\<hr>](https://www.w3schools.com/tags/tag_hr.asp "<hr>")    | Defines a thematic change in the content |
| [\<br>](https://www.w3schools.com/tags/tag_br.asp "<br>")    | Inserts a single line break              |
| [\<pre>](https://www.w3schools.com/tags/tag_pre.asp "<pre>") | Defines pre-formatted text               |

# HTML段落

The HTML `<p>` element defines a paragraph.

HTML `<p>` 元素定义了一个段落。

A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph. &#x20;

段落总是从新行开始，浏览器会自动在段落前后添加一些白色（边距）。

```html
<p>This is a paragraph.</p>  
<p>This is another paragraph.</p>
```

# HTML显示

You cannot be sure how HTML will be displayed. &#x20;

您无法确定HTML将如何显示。

Large or small screens, and resized windows will create different results. &#x20;

大屏幕或小屏幕以及调整大小的窗口将创建不同的结果。

With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code. &#x20;

使用HTML，您不能通过在HTML代码中添加额外的空格或额外的行来更改显示。

The browser will automatically remove any extra spaces and lines when the page is displayed: &#x20;

浏览器将在显示页面时自动删除任何多余的空格和行：

```html
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser
ignores it.
</p>

```

# HTML水平规则

The `<hr>` tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.

`<hr>` 标签在HTML页面中定义了一个主题分隔符，并且通常显示为水平线。

The `<hr>` element is used to separate content (or define a change) in an HTML page:

`<hr>` 元素用于分隔HTML页面中的内容（或定义更改）：

```html
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>
```

The `<hr>` tag is an empty tag, which means that it has no end tag.

`<hr>` 标签是一个空标签，这意味着它没有结束标签。

# HTML换行符

The HTML `<br>` element defines a line break.

HTML `<br>` 元素定义了一个换行符。

Use `<br>` if you want a line break (a new line) without starting a new paragraph:

如果你想在不开始新段落的情况下使用换行符（一个新行），请使用 `<br>` ：

```html
<p>This is<br>a paragraph<br>with line breaks.</p>
```

The `<br>` tag is an empty tag, which means that it has no end tag.

`<br>` 标签是一个空标签，这意味着它没有结束标签

# 诗歌问题

This poem will display on a single line:

这首诗将显示在一行：

```html
<p>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</p>
```

# 解决方案

The HTML `<pre>` element defines preformatted text.

HTML `<pre>` 元素定义了预格式化文本。

The text inside a `<pre>` element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:

`<pre>` 元素中的文本以固定宽度的字体（通常为Courier）显示，并且保留空格和换行符：

```html
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>
```
