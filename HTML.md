# HTML
## 1.什么是HTML语义化，有什么好处？

​	web语义化是指HTML标记表示页面包含的信息，包含了HTML标签的语义化和CSS命名的语义化。HTML标签的语义化是指：通过使用包含语义的标签恰当的表示文档结构。CSS命名的语义化是指：为HTML标签添加有意义的class和id补充未表达的语义。

​	1.去掉样式后页面清晰的结构。2.盲人使用读屏器更好的阅读。3.搜索引擎更好地理解页面，有利于SEO收录。3.便于团队项目的可持续运作及维护。

## 2.介绍HTML文件的第一行代码

​	<!DOCTYPE>，必须位于HTML文档的头部，告诉浏览器页面中编写HTML代码的版本，以便浏览器能正确的浏览。

## 3.行内元素有哪些？块级元素有哪些？

​	行内元素有:span/strong/a/b/em/img/input/label
​	块级元素有:div/p/form/ul/li/ol/hr

## 4.说说浏览器内核？

​	浏览器内核主要分成两个部分：渲染引擎和JS引擎。
​	渲染引擎主要负责取得网页的内容，JS引擎解析和执行js来实现网页的动态效果。
​	Trident：IE浏览器。
​	Geckos：FireFox Mozilla。
​	Presto：Opera。
​	Webkit：Safari Chrome。 

## 5.meta viewport是做什么用的，怎么写？

```
<meta name="viewport" content="width=device-width,user-scalable=no,initial-scale=1.0,maximum-scale=1.0,minumun-scale=1.0">
```

## 6.HTML5新增的特性

​	新增图像位置存储等功能。
​	canvas，localStorage，sessionStorage,footer,header,aside,nav,section

## 7.img的title和alt有什么区别

​	title是鼠标滑动到图片元素上面显示，alt是图片内容的等价描述，当图片无法加载时显示，可提高图片高可访问性。



