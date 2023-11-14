# H5-Comments

## 目录

-   [Comment Tag](#Comment-Tag)
-   [Add Comments](#Add-Comments)
-   [Hide Content](#Hide-Content)
-   [Hide Inline Content](#Hide-Inline-Content)

> 📌HTML注释

HTML comments are not displayed in the browser, but they can help document your HTML source code. &#x20;

HTML注释不会显示在浏览器中，但它们可以帮助您记录HTML源代码。

# `Comment Tag`

> 📌HTML标记注释

You can add comments to your HTML source by using the following syntax: &#x20;

您可以使用以下语法向HTML源添加注释：

```html
<!-- Write your comments here -->
```

Notice that there is an exclamation point (!) in the start tag, but not in the end tag. &#x20;

注意这里有一个感叹号（！）在开始标签中，但不在结束标签中。

> 📌**Note:** Comments are not displayed by the browser, but they can help document your HTML source code.注意：注释不显示在浏览器中，但它们可以帮助记录HTML源代码。

# `Add Comments`

> 📌HTML添加评论

With comments you can place notifications and reminders in your HTML code: &#x20;
通过注释，您可以在HTML代码中放置通知和提醒：

```html
<!-- This is a comment -->

<p>This is a paragraph.</p>

<!-- Remember to add more information here -->
```

# `Hide Content`

> 📌HTML隐藏内容

Comments can be used to hide content. &#x20;

注释可用于隐藏内容。

This can be helpful if you hide content temporarily: &#x20;

如果您暂时隐藏内容，这可能会很有帮助：

```html
<p>This is a paragraph.</p>

<!-- <p>This is another paragraph </p> -->

<p>This is a paragraph too.</p>
```

You can also hide more than one line. Everything between the `<!--` and the `-->` will be hidden from the display.

也可以隐藏多行。 `<!--` 和 `-->` 之间的所有内容都将从显示器中隐藏。

```html
<p>This is a paragraph.</p>
<!--
<p>Look at this cool image:</p>
<img border="0" src="pic_trulli.jpg" alt="Trulli">
-->
<p>This is a paragraph too.</p>
```

Comments are also great for debugging HTML, because you can comment out HTML lines of code, one at a time, to search for errors. &#x20;

注释对于调试HTML也非常有用，因为您可以一次注释掉一行HTML代码，以查找错误。

# `Hide Inline Content`

> 📌HTML隐藏内联内容

Comments can be used to hide parts in the middle of the HTML code. &#x20;
注释可以用来隐藏HTML代码中间的部分。

```html
<p>This <!-- great text --> is a paragraph.</p>
```
