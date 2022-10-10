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

## 标题
要创建标题，请在单词或短语前面添加井号 **#** 。 # 的数量代表了标题的级别。

<img class="inline" src="images/markdown_00.png"/>

> 不同的 Markdown 应用程序处理 # 和标题之间的空格方式并不一致。为了兼容考虑，请用一个空格在 # 和标题之间进行分隔。

## 段落
要创建段落，请使用空白行将**一行**或多行文本进行分隔。

<img class="inline" src="images/markdown_01.png"/>

> 不要用空格（spaces）或制表符（ tabs）缩进段落。

## 换行
在一行的末尾添加**两个**或多个空格，然后按回车键,即可创建一个换行。

<img class="inline" src="images/markdown_02.png"/>

## 强调
通过将文本设置为粗体或斜体来强调其重要性。

### 粗体（Bold）
要加粗文本，请在单词或短语的前后各添加**两个**星号（asterisks）或下划线（underscores）。

<img class="inline" src="images/markdown_03.png"/>

### 斜体（Italic）
要用斜体显示文本，请在单词或短语前后添加**一个**星号（asterisk）或下划线（underscore）。

<img class="inline" src="images/markdown_04.png"/>

### 粗体（Bold）和斜体（Italic）
要**同时**用粗体和斜体突出显示文本，请在单词或短语的前后各添加**三个**星号或下划线。

<img class="inline" src="images/markdown_05.png"/>

## 引用
- 要创建块引用，请在段落前添加一个 **>** 符号。

- 多个段落的块引用
块引用可以包含多个段落。为段落之间的**空白行**添加一个 > 符号。

- 嵌套块引用
块引用可以嵌套。在要嵌套的段落前添加一个 **>>** 符号。

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

##  代码
要将单词或短语表示为代码，请将其包裹在反引号 (`) 中。

<img class="inline" src="images/markdown_11.png"/>

如果你要表示为代码的单词或短语中包含一个或多个反引号，则可以通过将单词或短语包裹在双反引号(``)中。

<img class="inline" src="images/markdown_12.png"/>

- 代码块
要创建代码块，请将代码块的每一行缩进至少四个空格或一个制表符。
    <html>
      <head>
      </head>
    </html>

根据Markdown处理器或编辑器的不同，您将在代码块之前和之后的行上使用三个反引号（(```）或三个波浪号（~~~）。
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

{% include links.html %}
