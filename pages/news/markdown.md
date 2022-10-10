---
title: Markdown
keywords: help
last_updated: Oct 10, 2022
summary: ""
sidebar: mydoc_sidebar
permalink: markdown.html
folder: news
---

Markdown是一种轻量级标记语言，排版语法简洁，让人们更多地关注内容本身而非排版。它使用易读易写的纯文本格式编写文档，可与HTML混编，可导出 HTML、PDF 以及本身的 .md 格式的文件。因简洁、高效、易读、易写，Markdown被大量使用，如Github、Wikipedia、简书等。

<br>
## 标题
要创建标题，请在单词或短语前面添加井号 **#** 。 # 的数量代表了标题的级别。

<img class="inline" src="images/markdown_00.png"/>

> 不同的 Markdown 应用程序处理 # 和标题之间的空格方式并不一致。为了兼容考虑，请用一个空格在 # 和标题之间进行分隔。


<br>
## 段落
要创建段落，请使用空白行将**一行**或多行文本进行分隔。

<img class="inline" src="images/markdown_01.png"/>

> 不要用空格（spaces）或制表符（ tabs）缩进段落。


<br>
## 换行
在一行的末尾添加**两个**或多个空格，然后按回车键,即可创建一个换行。

<img class="inline" src="images/markdown_02.png"/>


<br>
## 强调
通过将文本设置为粗体或斜体来强调其重要性。

- 粗体（Bold）
要加粗文本，请在单词或短语的前后各添加**两个**星号（asterisks）或下划线（underscores）。

<img class="inline" src="images/markdown_03.png"/>

- 斜体（Italic）
要用斜体显示文本，请在单词或短语前后添加**一个**星号（asterisk）或下划线（underscore）。

<img class="inline" src="images/markdown_04.png"/>

- 粗体（Bold）和斜体（Italic）
要**同时**用粗体和斜体突出显示文本，请在单词或短语的前后各添加**三个**星号或下划线。

<img class="inline" src="images/markdown_05.png"/>

- 删除线
若要删除单词，请在单词前后使用**两个**波浪号**~~**。


<br>
## 引用
- 要创建块引用，请在段落前添加一个 **>** 符号。

- 多个段落的块引用
块引用可以包含多个段落。为段落之间的**空白行**添加一个 > 符号。

- 嵌套块引用
块引用可以嵌套。在要嵌套的段落前添加一个 **>>** 符号。


<br>
## 列表
- 有序列表

    要创建有序列表，请在每个列表项前添加数字并紧跟一个英文句点。数字不必按数学顺序排列，但是列表应当以数字 1 起始。

<img class="inline" src="images/markdown_06.png"/>

- 无序列表

    要创建无序列表，请在每个列表项前面添加破折号 (-)、星号 (*) 或加号 (+) 。缩进一个或多个列表项可创建嵌套列表。

<img class="inline" src="images/markdown_07.png"/>

- 在列表中嵌套其他元素

    要在保留列表连续性的同时在列表中添加另一种元素，请将该元素缩进四个空格或一个制表符，如下例所示：

<img class="inline" src="images/markdown_08.png"/>

<img class="inline" src="images/markdown_09.png"/>

- 代码块

    代码块通常采用四个空格或一个制表符缩进。当它们被放在列表中时，请将它们缩进八个空格或两个制表符。

<img class="inline" src="images/markdown_10.png"/>


<br>
##  代码
- 要将单词或短语表示为代码，请将其包裹在反引号 **`** 中。

<img class="inline" src="images/markdown_11.png"/>

- 如果你要表示为代码的单词或短语中包含一个或多个反引号，则可以通过将单词或短语包裹在双反引号**``**中。

<img class="inline" src="images/markdown_12.png"/>

- 要创建代码块，请将代码块的每一行缩进至少四个空格或一个制表符。

根据Markdown处理器或编辑器的不同，您将在代码块之前和之后的行上使用*三个*反引号**```**或三个波浪号**~~~**。
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```


<br>
## 分隔线
要创建分隔线，请在**单独一行**上使用**三个**或多个星号 (***)、破折号 (---) 或下划线 (___) ，并且不能包含其他内容。
> 为了兼容性，请在分隔线的前后均添加空白行。


<br>
## 链接
- 超链接Markdown语法代码：[超链接显示名](超链接地址 "超链接title")
- 使用尖括号可以很方便地把URL或者email地址变成可点击的链接。


<br>
## 引用类型链接

引用样式链接是一种特殊的链接，它使URL在Markdown中更易于显示和阅读。参考样式链接分为两部分：与文本保持内联的部分以及存储在文件中其他位置的部分，以使文本易于阅读。

- 链接的第一部分格式
引用类型的链接的第一部分使用两组括号进行格式设置。第一组方括号包围应显示为链接的文本。第二组括号显示了一个标签，该标签用于指向您存储在文档其他位置的链接。

尽管不是必需的，可以在第一组和第二组括号之间包含一个空格。第二组括号中的标签不区分大小写，可以包含字母，数字，空格或标点符号。

以下示例格式对于链接的第一部分效果相同：

[hobbit-hole][1]

- 链接的第二部分格式
引用类型链接的第二部分使用以下属性设置格式：

放在括号中的标签，其后紧跟一个冒号和至少一个空格（例如[label]:）。
链接的URL，可以选择将其括在尖括号中。
链接的可选标题，可以将其括在双引号，单引号或括号中。
以下示例格式对于链接的第二部分效果相同：

[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)
可以将链接的第二部分放在Markdown文档中的任何位置。有些人将它们放在出现的段落之后，有些人则将它们放在文档的末尾（例如尾注或脚注）。


<br>
## 图片

- 要添加图像，请使用感叹号 (!), 然后在方括号增加替代文本，图片链接放在圆括号里，括号里的链接后可以增加一个可选的图片标题文本。

- 插入图片Markdown语法代码：![图片alt](图片链接 "图片title")。

- 对应的HTML代码：<img src="图片链接" alt="图片alt" title="图片title">

- 给图片增加链接，请将图像的Markdown 括在方括号中，然后将链接添加在圆括号中。

[![沙漠中的岩石图片](/assets/img/shiprock.jpg "Shiprock")](https://markdown.com.cn)


<br>
## 表格
要添加表，请使用三个或多个连字符（---）创建每列的标题，并使用管道（|）分隔每列。您可以选择在表的任一端添加管道。

<img class="inline" src="images/markdown_13.png"/>

- 对齐
您可以通过在标题行中的连字符的左侧，右侧或两侧添加冒号（:），将列中的文本对齐到左侧，右侧或中心。

<img class="inline" src="images/markdown_14.png"/>



<br>
## 脚注
脚注使您可以添加注释和参考，而不会使文档正文混乱。当您创建脚注时，带有脚注的上标数字会出现在您添加脚注参考的位置。读者可以单击链接以跳至页面底部的脚注内容。

要创建脚注参考，请在方括号（[^1]）内添加插入符号和标识符。标识符可以是数字或单词，但不能包含空格或制表符。标识符仅将脚注参考与脚注本身相关联-在输出中，脚注按顺序编号。

在括号内使用另一个插入符号和数字添加脚注，并用冒号和文本（[^1]: My footnote.）。您不必在文档末尾添加脚注。您可以将它们放在除列表，块引号和表之类的其他元素之外的任何位置。


<img class="inline" src="images/markdown_15.png"/>


<br>
## 任务列表
任务列表使您可以创建带有复选框的项目列表。在支持任务列表的Markdown应用程序中，复选框将显示在内容旁边。要创建任务列表，请在任务列表项之前添加破折号-和方括号[ ]，并在[ ]前面加上空格。要选择一个复选框，请在方括号[x]之间添加 x 。

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media


{% include links.html %}
