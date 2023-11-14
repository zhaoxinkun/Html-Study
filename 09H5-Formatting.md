# H5-Formatting&#x20;

## 目录

-   [Formatting Elements](#Formatting-Elements)
-   [\<b>/\<strong> ](#bstrong-)
-   [\<i>/\<em>](#iem)
-   [\<small>](#small)
-   [\<mark>](#mark)
-   [\<del> ](#del-)
-   [\<s>](#s)
-   [\<ins>](#ins)
-   [\<sub> ](#sub-)
-   [\<sup> ](#sup-)

> 📌文本格式

| Tag                                                                   | Description                                          |
| --------------------------------------------------------------------- | ---------------------------------------------------- |
| [\<b>](https://www.w3schools.com/tags/tag_b.asp "<b>")                | Defines bold text                                    |
| [\<em>](https://www.w3schools.com/tags/tag_em.asp "<em>")             | Defines emphasized text                              |
| [\<i>](https://www.w3schools.com/tags/tag_i.asp "<i>")                | Defines a part of text in an alternate voice or mood |
| [\<small>](https://www.w3schools.com/tags/tag_small.asp "<small>")    | Defines smaller text                                 |
| [\<strong>](https://www.w3schools.com/tags/tag_strong.asp "<strong>") | Defines important text                               |
| [\<sub>](https://www.w3schools.com/tags/tag_sub.asp "<sub>")          | Defines subscripted text                             |
| [\<sup>](https://www.w3schools.com/tags/tag_sup.asp "<sup>")          | Defines superscripted text                           |
| [\<ins>](https://www.w3schools.com/tags/tag_ins.asp "<ins>")          | Defines inserted text                                |
| [\<del>](https://www.w3schools.com/tags/tag_del.asp "<del>")          | Defines deleted text                                 |
| \<s>                                                                  | An error line                                        |
| [\<mark>](https://www.w3schools.com/tags/tag_mark.asp "<mark>")       | Defines marked/highlighted text                      |

# Formatting Elements

Formatting elements were designed to display special types of text: &#x20;

格式化元素旨在显示特殊类型的文本：

-   `<b>` - Bold text `<b>` -粗体文本
-   `<strong>` - Important text `<strong>` -重要文本
-   `<i>` - Italic text `<i>` -斜体文本
-   `<em>` - Emphasized text `<em>` -强调文本
-   `<mark>` - Marked text `<mark>` -标记文本
-   `<small>` - Smaller text `<small>` -较小的文本
-   `<del>` - Deleted text `<del>` -删除文本
-   `<ins>` - Inserted text `<ins>` -插入的文本
-   `<sub>` - Subscript text `<sub>` -下标文本
-   `<sup>` - Superscript text `<sup>` -上标文本

# `<b>/<strong> `

> 📌加粗元素

The HTML `<b>` element defines bold text, without any extra importance.

HTML `<b>` 元素定义粗体文本，没有任何额外的重要性。

```html
<b>This text is bold</b>
```

The HTML `<strong>` element defines text with strong importance. The content inside is typically displayed in bold.

HTML `<strong>` 元素定义了非常重要的文本。里面的内容通常以粗体显示。

```html
<strong>This text is important!</strong>
```

# `<i>/<em>`

> 📌倾斜元素

The HTML `<i>` element defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic.

HTML `<i>` 元素定义了文本的一部分，以替代的声音或语气。里面的内容通常以斜体显示。

**Tip:** The `<i>` tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.

提示： `<i>` 标签通常用于表示技术术语，来自另一种语言的短语，思想，船名等。

```html
<i>This text is italic</i>
```

The HTML `<em>` element defines emphasized text. The content inside is typically displayed in italic.

HTML `<em>` 元素定义了强调的文本。里面的内容通常以斜体显示。

**Tip:** A screen reader will pronounce the words in `<em>` with an emphasis, using verbal stress.

提示：屏幕阅读器会使用动词重音来强调 `<em>` 中的单词。

```html
<em>This text is emphasized</em>
```

# `<small>`

> 📌较小元素

The HTML `<small>` element defines smaller text:

HTML `<small>` 元素定义较小的文本：

```html
<small>This is some smaller text.</small>
```

# `<mark>`

> 📌高亮元素

The HTML `<mark>` element defines text that should be marked or highlighted:

HTML `<mark>` 元素定义了应该标记或高亮显示的文本：

```html
<p>Do not forget to buy <mark>milk</mark> today.</p>
```

# `<del> `

> 📌删除线元素

The HTML `<del>` element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text:

HTML `<del>` 元素定义了从文档中删除的文本。浏览器通常会在删除的文本中划一行：

```html
<p>My favorite color is <del>blue</del> red.</p>
```

# `<s>`

> 📌错误线元素

其实就是错误线，和del效果一致，但是更加语义化罢了

# `<ins>`

> 📌插入元素

The HTML `<ins>` element defines a text that has been inserted into a document. Browsers will usually underline inserted text:

HTML `<ins>` 元素定义了一个插入到文档中的文本。浏览器通常会在插入的文本下面加下划线：

```html
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>
```

# `<sub> `

> 📌下标元素

The HTML `<sub>` element defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O:

HTML `<sub>` 元素定义下标文本。下标文本显示在正常行下半个字符，有时会以较小的字体呈现。下标文本可用于化学式，如H 2 O：

```html
<p>This is <sub>subscripted</sub> text.</p>
```

# `<sup> `

> 📌上标元素

The HTML `<sup>` element defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW\[1]:

HTML `<sup>` 元素定义上标文本。上标文本显示在正常行上方的半个字符，有时以较小的字体呈现。上标文本可用于脚注，如WWW \[1] ：

```html
<p>This is <sup>superscripted</sup> text.</p>
```
