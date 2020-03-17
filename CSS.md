# CSS

```
“你三四月做的事,七八月自有答案”
```

## 1.CSS引入方式

​	1.行内样式，使用style属性引入CSS样式。
​	2.内部样式表，在<style></style>中书写CSS代码。
​	3.外部样式表，以css文件名结尾引入外部样式表。

## 2.CSS盒模型，标准盒模型和IE盒模型

​	1.标准盒模型，margin,padding,border,content,width=content.
​	2.IE盒模型,margin,padding,border,content.width=content+padding+content.

## 3.css选择符，哪些属性可以继承

​	1.ID选择器，CLASS类选择器，标签选择器，子代选择器，后代选择器，通配符选择器，属性选择器，伪类选择器。
​	2.可继承的属性:font-size,font-family,color
​	不可继承的属性:border,padding,margin,height,width  

## 4.CSS优先级如何计算？

​	优先级就近原则，同权重情况下样式定义最近为准
​	载入样式以最后载入的定位为准
​	!important > id > class > tag
​	!important比内联样式优先级高
​	权重值：!important-无穷 行间样式-1000 id-100 class/属性选择器/伪类hover -10  标签选择器/伪元素after-1 通配符-0

## 5.position的值？相对于什么定位？

​	position有五个值，static,relative,absolute,fixed,inherit.static为默认值，普通文档流。relative为相对定位，相对于文档流中之前位置定位，不脱离文档流。absolute为绝对定位，相对于最近父元素非static值定位，脱离文档流。fixed为固定定位，相对于浏览器可视窗口定位，脱离文档流,inherit规定从父元素继承position属性的值。

## 6.CSS3有哪些特性？

​	过渡transition 动画animaiton 形状转换 transform  阴影 box-shadow 边框图片border-image 边框圆角border-radius 换行word-break:normal。
​	超出省略号：overflow:hidden;white-space:nowrap;text-overflow:ellipsis;
​	颜色rgba 渐变linear 弹性布局flex

## 7.经常遇到的浏览器兼容性问题有哪些？原因解决方法是什么？

​	png24位图片在ie6浏览器上出现背景，解决方案是做成png8.
​	浏览器默认的margin和padding不同，解决方案是加一个全局的*{margin：0;padding:0;}来统一.
​	chrome浏览器中文界面会将小于12px的文本强制按照12px显示，可通过-webkit-text-size-adjust:none解决.

## 8.margin和padding分别适合什么场景使用？

​	margin是用来隔开元素和元素之间的间距，padding是用来隔开元素与内容的间隔，margin是用来布局分开元素，是元素和元素互不相干，padding用来给元素和内容之间的间隔，让内容和元素之间有一段间距。

## 9.css优化/提高性能的方法有哪些？

​	尽量将样式写在单独的css文件里面，内容和样式分离，易于管理和维护。减少页面体积。css文件可以被缓存，重用。
​	不使用@import。
​	避免使用复杂的选择器，精简样式文件，利用css继承减少代码量。避免!important

。