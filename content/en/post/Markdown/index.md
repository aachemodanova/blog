---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Markdown"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2023-04-07T15:12:01+03:00
lastmod: 2023-04-07T15:12:01+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Markdown is a text markup language. Such texts are easy to write and read. They can be easily converted to HTML. Most programmers prefer Markdown for writing documentation, describing their projects, writing blogs, and so on.

What does it mean?

A "markup language" is simply a set of conventions, rules.

Let's say you're texting a friend. They cannot make text bold or italic. You agree with a friend: if I write *something* like this between the asterisks, then consider it as italic text. And if I write **something** between two asterisks, then consider that this is bold text. You made up the rules.

Markdown is a set of such rules.

The rules are clear to different programs and sites. For example, the "Questions and Answers" in the Hexlet lessons support Markdown. This means that you can write texts there according to Markdown rules, and after clicking “Submit”, the markup will become real: text in single asterisks will become italic, text in double asterisks will become bold, and so on. This is the conversion from Markdown to HTML.
Why is this needed?

To add markup where no real markup is possible. For example, in a simple text file or in the same SMS, where it is impossible to bold, create headings, highlight quotes, etc.
For more convenient writing of texts for subsequent conversion to HTML or other formats.

Markdown Syntax

This is a quick reference to the basic elements of Markdown syntax. There is no single standard, and different versions of Markdown may differ in details. But the basic elements from the list below are supported in all standards.
Text selection

*This text will be italicized*
_This text will be italic (italic)_

**This text will be bold**
__This text will be bold__

_You can **insert** one type into another_

Links

https://hexlet.io - the text of a simple link will become a clickable link automatically

You can make any text a link:

[This is a Hexlet link](https://hexlet.io)

Quote

>That's a wise quote
> wise man.

Images

![This is optional alt text](/assets/images/markdown/markdown.png)

Lists

Unnumbered list:

* Paragraph
*One more item
   * Subparagraph
   * Another sub-item

Numbered list:

1. Item
1. One more point
   1. Subparagraph
   1. One more subparagraph

You can use any numbers in a numbered list - it doesn't matter. When converted to HTML or another format, the numbers will become correct and consistent (1, 2, 3, etc.).
