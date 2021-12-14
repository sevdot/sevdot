## Html 全局属性

每个元素都规定自己的属性，有的属性是特有的，只有特有某几个元素才有，比如：`src` 仅 `img` 、`video` 、`audio` 等元素才有，`h1~h6` 和 `p` 等元素没有，有的属性属于全局属性，几乎所有的元素都有，如 `id`。


有哪些全局属性呢？下面来将了解以下这些全局属性的使用：

- id
- class
- style
- title
- accesskey
- contenteditable
- contextmenu
- dir
- draggable
- dropzone
- hidden
- lang
- spellcheck
- tabindex

​

## id 属性
id 属性用来给元素分配一个唯一的标识符。这种标识符通常用来将样式应用到元素上或在 JavaScript 程序中用来选择该元素。id 属性还可以用来导航到文档中特定位置。
## class 属性
class 属性用来将元素归类。这样做通常是为了能够找出文档中的某一类元素或为某一类元素应用 CSS 样式。一个元素可以被归入多个类别，为此在 class 属性值中提供多个用空格分割的类名即可。类名可以随便取，不过最好取点具有实际含义的，文档中拥有许多元素类别时尤其如此。
## title 属性
title 属性提供了元素的额外信息。浏览器通常用这些东西显示工具提示。
## style 属性
style 属性用来直接在元素身上定义 CSS 样式（这是在 style 元素或外部样式表中定义样式之外的一种选择）。
## accesskey 属性
使用 accesskey 属性可以设置一个或几个用来选择页面上的元素的快捷键，让浏览网页用户可以使用快捷键访问经常用到的元素，用来触发 accesskey 机制的按键组合因平台而异，在 Windows 系统上是同时按下 `alt` 键和 accesskey 属性值对应的键；在是 Mac 系统上是同时按下 `option` 键和 accesskey 属性值对应的键。
```html
<!DOCTYPE HTML>
<html>
  <head>
    <title>示例</title>
  </head>
  <body>
    <form>
      姓名:<input type="text" name="name" accessley="n" />
      <br/>
      密码:<input type="password" name="password" accessley="p" />
       <br/>
      <input type="submit" value="loin" accessley="s" />
    </form>
  </body>
</html>
```
代码所示为 3 个 `input` 元素添加了 accesskey 属性，在 Mac 系统上，用户可以按 `option` 键和 `n` 键焦点转移到输入用户名，按 `option` 键和 `p` 键焦点切换到输入密码。然后按 `option + s` 等于按下按钮提交表单。
​

## contenteditable 属性
contenteditable 属性是 HTML5 中新增加的属性，其用途是可以让用户能够修改上面的内容。
​

## contextmenu 属性
contextmenu 属性用来为元素设定快捷菜单。这种菜单会在收到触发的时候弹出来。
​

## dir 属性
dir 属性用来规定元素中文字的方向，其有效值有两个：ltr（用于从左到右的文字）和 rtl（用于从右到左的文字）。
​

## draggable 属性
darggable 属性是 HTML5支持拖放操作方式之一，用来表示元素是否可以被拖放。
​

## dropzone 属性
dropzone 属性是 HTML5 支持拖放操作方式之一，与 draggable 属性搭配使用。


## hidden 属性
hidden 属性是个布尔属性，表示相关元素当前毋需关注。浏览器对它的处理方式隐藏相关元素。把 hidden 属性应到一个元素之后，浏览器干脆不去显示该元素，仿佛 HTML 文档中没有这个元素。
​

## lang 属性
lang 属性用于说明元素内容使用的语音。 lang 属性必须使用有效的 ISO 语言代码。不过要注意，语言是个复杂的技术性问题。
​

使用 lang 属性的目的是让浏览器调整其表达元素内容的方式。比如说，改变使用引号，在使用了文字朗读器的情况下正确发音。
​

lang 属性还可以用来选择指定语言的内容，以便只显示用户所选语言的内容或对其应用样式。
​

## spellcheck 属性
spellcheck 属性用来表明浏览器是否应该对元素的内容进行拼写检查。这个属性只有用在用户可以编辑的元素上时才有意义。
​

## tabindex 属性
HTML 页面上的键盘焦点可以通过 Tab 键在各元素之间切换。用 tabindex 属性可以改变默认的转移顺序。


我最近在读《HTML5 权威指南》，以上内容来自上面的整理。
