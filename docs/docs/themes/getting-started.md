# Liquid标记语言入门

> Getting started with the Liquid markup language [原文](https://shopify.dev/docs/themes/getting-started)

## 什么是模板语言？

网站设计者和开发者可以使用模板语言构建将静态内容（多页相同）和动态内容（从一页更改为下一页）相结合的网页。模板语言使可以重新使用定义网页布局的静态元素，同时使用Shopify存储的数据动态填充页面。静态元素是用HTML编写的，动态元素是用Liquid编写的。文件中的Liquid元素充当占位符：当编译文件中的代码并发送到浏览器时，Liquid将被安装主题的Shopify存储的数据所取代。

<details>
<summary>原文</summary>
<pre>
<code>

What is a template language?
Website designers and developers can use a template language to build webpages that combine static content, which is the same on multiple pages, and dynamic content, which changes from one page to the next. A template language makes it possible to re-use the static elements that define the layout of a webpage, while dynamically populating the page with data from a Shopify store. The static elements are written in HTML, and the dynamic elements are written in Liquid. The Liquid elements in a file act as placeholders: when the code in the file is compiled and sent to the browser, the Liquid is replaced by data from the Shopify store where the theme is installed.

</code>
</pre>
</details>

## Liquid语法

与传统编程语言一样，Liquid具有语法，与变量交互，并包含输出和逻辑等结构。由于其可读的语法，Liquid构造易于识别，并且可以通过两组分隔符与HTML区分开来：双花括号分隔符 `{{}}` 表示输出；花括号百分比分隔符`{% %}`表示逻辑和控制流。

Liquid代码有三个主要功能：

- [对象(Objects)](#对象)

- [标签(Tags)](#标签)

- [过滤器(Filters)](#过滤器)


<details>
<summary>原文</summary>
<pre>
<code>

Liquid syntax
Like traditional programming languages, Liquid has a syntax, interacts with variables, and includes constructs such as output and logic. Due to its readable syntax, Liquid constructs are easy to recognize, and can be distinguished from HTML by two sets of delimiters: the double curly brace delimiters {{ }}, which denote output, and the curly brace percentage delimiters {% %}, which denote logic and control flow.

There are three main features of Liquid code:

Objects
Tags
Filters

</code>
</pre>
</details>

