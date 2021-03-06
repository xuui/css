# Xuui CSS
Own CSS framework. A long time ago.

version: 1.2 

这个是 xuui.net 以及以前网页项目使用的 HTML 样式重置（CSS Reset）的基本模板文件。  
包括基本的排班样式、栅格、表格、表单、媒体组件。  
主要有 Xu.hel 维护, 使用 BSD 协议发布。  
基于 pure.css 定制。  

## HTML 完整标签
```
<!DOCTYPE>  	定义文档类型。
<html> 	定义 HTML 文档。
<title> 	定义文档的标题。
<body> 	定义文档的主体。
<h1> to <h6> 	定义 HTML 标题。
<p> 	定义段落。
<br> 	定义简单的折行。
<hr> 	定义水平线。
<!--...--> 	定义注释。

格式
<acronym> 	定义只取首字母的缩写。
<abbr> 	定义缩写。
<address> 	定义文档作者或拥有者的联系信息。
<b> 	定义粗体文本。
<bdi> 	定义文本的文本方向，使其脱离其周围文本的方向设置。
<bdo> 	定义文字方向。
<big> 	定义大号文本。
<blockquote> 	定义长的引用。
<center> 	不赞成使用。定义居中文本。
<cite> 	定义引用(citation)。
<code> 	定义计算机代码文本。
<del> 	定义被删除文本。
<dfn> 	定义定义项目。
<em> 	定义强调文本。
<font> 	不赞成使用。定义文本的字体、尺寸和颜色
<i> 	定义斜体文本。
<ins> 	定义被插入文本。
<kbd> 	定义键盘文本。
<mark> 	定义有记号的文本。
<meter> 	定义预定义范围内的度量。
<pre> 	定义预格式文本。
<progress> 	定义任何类型的任务的进度。
<q> 	定义短的引用。
<rp> 	定义若浏览器不支持 ruby 元素显示的内容。
<rt> 	定义 ruby 注释的解释。
<ruby> 	定义 ruby 注释。
<s> 	不赞成使用。定义加删除线的文本。
<samp> 	定义计算机代码样本。
<small> 	定义小号文本。
<strike> 	不赞成使用。定义加删除线文本。
<strong> 	定义语气更为强烈的强调文本。
<sup> 	定义上标文本。
<sub> 	定义下标文本。
<time> 	定义日期/时间。
<tt> 	定义打字机文本。
<u> 	不赞成使用。定义下划线文本。
<var> 	定义文本的变量部分。
<wbr> 	定义可能的换行符。

表单
<form> 	定义供用户输入的 HTML 表单。
<input> 	定义输入控件。
<textarea> 	定义多行的文本输入控件。
<button> 	定义按钮。
<select> 	定义选择列表（下拉列表）。
<optgroup> 	定义选择列表中相关选项的组合。
<option> 	定义选择列表中的选项。
<label> 	定义 input 元素的标注。
<fieldset> 	定义围绕表单中元素的边框。
<legend> 	定义 fieldset 元素的标题。
<isindex> 	不赞成使用。定义与文档相关的可搜索索引。
<datalist> 	定义下拉列表。
<keygen> 	定义生成密钥。
<output> 	定义输出的一些类型。

框架
<frame> 	定义框架集的窗口或框架。
<frameset> 	定义框架集。
<noframes> 	定义针对不支持框架的用户的替代内容。
<iframe> 	定义内联框架。

图像
<img> 	定义图像。
<map> 	定义图像映射。
<area> 	定义图像地图内部的区域。
<canvas> 	定义图形。
<figcaption> 	定义 figure 元素的标题。
<figure> 	定义媒介内容的分组，以及它们的标题。

音频/视频
<audio> 	定义声音内容。
<source> 	定义媒介源。
<track> 	定义用在媒体播放器中的文本轨道。
<video> 	定义视频。

链接
<a> 	定义锚。
<link> 	定义文档与外部资源的关系。
<nav> 	定义导航链接。

列表
<ul> 	定义无序列表。
<ol> 	定义有序列表。
<li> 	定义列表的项目。
<dir> 	不赞成使用。定义目录列表。
<dl> 	定义定义列表。
<dt> 	定义定义列表中的项目。
<dd> 	定义定义列表中项目的描述。
<menu> 	定义命令的菜单/列表。
<menuitem> 	定义用户可以从弹出菜单调用的命令/菜单项目。
<command> 	定义命令按钮。

表格
<table> 	定义表格
<caption> 	定义表格标题。
<th> 	定义表格中的表头单元格。
<tr> 	定义表格中的行。
<td> 	定义表格中的单元。
<thead> 	定义表格中的表头内容。
<tbody> 	定义表格中的主体内容。
<tfoot> 	定义表格中的表注内容（脚注）。
<col> 	定义表格中一个或多个列的属性值。
<colgroup> 	定义表格中供格式化的列组。

样式/节
<style> 	定义文档的样式信息。
<div> 	定义文档中的节。
<span> 	定义文档中的节。
<header> 	定义 section 或 page 的页眉。
<footer> 	定义 section 或 page 的页脚。
<section> 	定义 section。
<article> 	定义文章。
<aside> 	定义页面内容之外的内容。
<details> 	定义元素的细节。
<dialog> 	定义对话框或窗口。
<summary> 	为 <details> 元素定义可见的标题。

元信息
<head> 	定义关于文档的信息。
<meta> 	定义关于 HTML 文档的元信息。
<base> 	定义页面中所有链接的默认地址或默认目标。
<basefont> 	不赞成使用。定义页面中文本的默认字体、颜色或尺寸。

编程
<script> 	定义客户端脚本。
<noscript> 	定义针对不支持客户端脚本的用户的替代内容。
<applet> 	不赞成使用。定义嵌入的 applet。
<embed> 	为外部应用程序（非 HTML）定义容器。
<object> 	定义嵌入的对象。
<param> 	定义对象的参数。
```

