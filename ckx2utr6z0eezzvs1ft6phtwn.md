## Html5 简介



大致的了解了 Web 前端开发的发展历史，知道 Web 开发包括 HTML、CSS 和 JavaScript 三个核心技术，其中 HTML 描述网页内容结构和含义，在 Web 前端开发中有着很重要的地位。

## 什么是 HTML
HTML 是  `H` yper `t` ext `M` arkup `L` anguage 即超文本标记语言的缩写。注意： **HTML 不是一种编程语言，而是一种**_**标记语言**_** (markup language)，标记语言是一套**_**标记标签**_** (markup tag)，HTML 使用**_**标记标签**_**来描述网页。**


HTML 的历史可以追溯到很久以前。1993 年 HTML 首次以因特网草案的形式发布。20 世纪 90 年代的人见证了 HTML 的高速发展，从 2.0 版，到 3.2 版和 4.0 版，再到 1999 年的 4.01 版，一直到现在正逐步普及的 HTML5。随着 HTML 的发展，W3C（万维网联盟）掌握了对 HTML 规范的控制权。


在快速发布了 HTML 的前 4 个版本之后，业界普遍认为 HTML 已经“无路可走”了，对 Web 标准的焦点也开始转移到了XML 和 XHTML，HTML 被放在次要位置。不过在此期间，HTML 体现了顽强的生命力，主要的网站内容还是基于 HTML的。为能支持新的 Web 应用，同时克服现有的缺点，HTML 迫切需要添加新功能，制定新规范。

HTML 发展历史，经过发展，HTML 逐渐形成标准，HTML 标准从诞生至今经过多次修订，以下是修订年表：


- HTML 超文本标记语言（第一版）—— 在 1993 年 6 月作为互联网工程工作小组（IETF）工作草案发布（并非标准）。

- HTML 2.0 —— 1995 年 11 月作为 RFC 1866 发布，在 RFC 2854 于2000 年 6 月发布之后被宣布已经过时。

- HTML 3.2 —— 1997 年 1 月14 日，W3C推荐标准。

- HTML 4.0 —— 1997年12 月18 日，W3C推荐标准。

- HTML 4.01（微小改进）—— 1999 年 12 月 24 日，W3C 推荐标准。

- HTML 5：HTML5 是公认的下一代 Web 语言，极大地提升了 Web 在富媒体、富内容和富应用等方面的能力，被喻为终将改变移动互联网的重要推手。



HTML5 需要成立相应的组织，并且肯定需要有人来负责。这正是下面这 3 个重要组织的工作：

- WHATWG：由来自 Apple、Mozilla、Google、Opera 等浏览器厂商的人组成，成立于 2004 年。WHATWG 开发HTML 和 Web 应用 API，同时为各浏览器厂商以及其他有意向的组织提供开放式合作。
- W3C：W3C 下辖的 HTML 工作组目前负责发布 HTML5 规范。
- IETF（Internet Engineering Task Force，因特网工程任务组）：这个任务组下辖 HTTP 等负责 Internet 协议的团队。HTML5 定义的一种新 API（WebSocket API）依赖于新的 WebSocket 协议，IETF 工作组正在开发这个协议。



## HTML5
现如今我们说的 HTML 其实是 HTML5，HTML5 不仅仅是 HTML 规范的最新版本，它还是一系列用来制作现代富 Web 内容的相关技术的总称。其中最重要的三项技术是 HTML5 核心规范、CSS（Cascading Style Sheets，层叠样式表）和 JavaScript。HTML5 核心规范定义用以标记内容的元素，并明确其含义。CSS 可用于控制标记过的内容呈现在用户面前的外貌。JavaScript 则可以用来操纵HTML文档的内容以及响应用户的操作，此外要想使用 HTML5 新增元素的一些为编程目的设计的特性也需要用到 JavaScript。


HTML5 与 HTML4.01 相比有哪些区别呢?


### 文档类型声明
HTML5 与 HTML 4.01 以及 XHTML1.0 在文档类型上有很大的改进，相比之下 HTML 文档类型声明要简单得多，在我最开始编写 HTML 代码的时候我很难记住声明代码，以下是三个版本对文档类型声明的比较：
**
**HTML4.01 **
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
"http://www.w3.org/TR/html4/loose.dtd">
```
**
**XHTML1.0 **

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
```
**
**HTML5 **
```html
<!DOCTYPE html>
```


### 设置页面字符编码
在设置页面字符编码上 HTML5 也相对简化了。

**HTML4 **
```
<meta http-equiv="content-type" content="text/html; charset=UTF-8">
```
**
**HTML5 **

```
<meta charset="UTF-8">
```


### 结构语义化
HTML4.01 没有体现结构语义化的标签，人们通常都是这样来表示网站的头部 `<div id="header">`。而 HTML5  在语义上却有很大的优势，提供了一些新的标签，比如 `<header>`  、`<nav>` 、 `<section>` 、 `<article>` 、 `<aside>` 、 `<footer>` 等。


### 新增元素
HTML5 新增许多元素。


![1589268747976-69682b0c-ea4e-4aca-a791-c3044bc8e95c.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1639289286750/lks-8Nqe8.png)

**新增的 input 类型：**

- `email` 邮件地址 
- `url` URL地址 
-  `number` 数字 
-  `range` 范围滑动条 
-  `date` 日期 
-  `search` 搜索
- `color` 颜色选择器



**新的内联元素：**

- `<meter>` 定义预定义范围内的度量

- `<progress>` 定义任何类型的任务的进度

- `<time>` 定义一个日期/时间

- `<mark>` 标签定义带有记号的文本



**新的内嵌元素：**

- `<video>` 定义视频

- `<audio>` 定义音频

- `<source>` 为媒介元素（比如 `<video>` 和 `<audio>`）定义媒介资源



**新的交互元素：**

- `<details>` 定义元素的细节

- `<datagrid>` 定义树列表 (tree-list) 中的数据

- `<datalist>` 定义选项列表

- `<menu>` 定义菜单列表

- `<command>` 定义命令按钮



### 新增 `<canvas>` 元素替代 flash
在前面介绍前端发展历史中说过，前端开发发展中有过一个插件称雄的时期，网站中充斥着许多** flash 插件**，**flash 插件**给 web 开发者带来许多麻烦。HTML5 提供 `<canvas>` 元素，通过 `<canvas>` 元素可以实现那些必须需要 **flash 插件**支持才能实现的功能。


### 废弃元素
HTML5 提倡语义与呈现分离，所以在 HTML5 中废弃了 HTML4.01 中提供页面展示的元素。


**能用 CSS 代替的元素**：

-  `<basefont>` 
-  `<big>` 
-  `<center>` 
-  `<font>` 
-  `<s>` 
-  `<strike>` 
-  `<tt>` 
-  `<u>`



**不再使用 Frame 框架，指支持 iframe框架**
**
**只有部分浏览器支持的元素：**

- `<applet>` 
-  `<bgsound>` 
-  `<blink>` 
- `<marquee>` 



### 本地存储
HTML5 Storage 提供了一种方式让网站能够把信息存储到你本地的计算机上，并在以后需要的时候进行获取。这个概念和Cookie 相似，区别是它是为了更大容量存储设计的。Cookie 的大小是受限的，并且每次你请求一个新的页面的时候Cookie 都会被发送过去，这使得 Cookie 速度很慢而且效率也不高。HTML5 的 Storage 是存储在你的计算机上，网站在页面加载完毕后可以通过 Javascript 来获取这些数据。


HTML5 提供了两种在客户端存储数据的新方法：

- localStorage - 没有时间限制的数据存储

- sessionStorage - 针对一个session的数据存储


这两天一直在看 《HTML5 权威指南》，以上内容就是来自上面。