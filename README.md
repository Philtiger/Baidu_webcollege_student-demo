# 零基础学院学习内容 
我一直认为自己能写出来一个页面，用框架让它变得不光是一个文档流就应该算是基础入门完毕了。 <br>
如果能在短时间再完成基础的巩固，而且能从容完成一系列任务，不妨也是在大学的生活中真正添加一点乐趣。 <br>
也算是自欺欺人吧，完成这里的任务也能写到项目经验里，大学毕业之后好歹这一栏不空着会好看一点。XD
***
简历codepen地址：[简历](https://codepen.io/philtiger/pen/eqYYZZ)
三种简历样式作业演示：[三种简历](https://philtiger.github.io/Baidu_webcollege_student-demo/three_style/resume.html)
***
### 第一堂课 2019/7/17
今天是参与学习的第一天，是晚上开始的，从白天一直在刷Js的题，突发奇想抽点时间再把基础过一编，就发现了这个地方（宝藏）；<br>
说起来先记录下第一堂课的记笔记方法把：
* 日期，学习的总用时，学习目标是什么，是否达成
* 哪些东西今天了解的比较透彻，说说自己的理解
* 哪些东西今天了解到了一些，还有哪些点需要后续继续深入阅读
* 哪些东西今天学了之后还有很多疑问没被解答，记录下来
#### 第一堂课作业 FLAG
66天巩固基础，其实蛮希望能提前完成的，从原生角度再熟悉一遍开发流程。
***
### 第二堂课 2019/7/18
  （学习时长：5h）<br>
简单的在线简历制作过程中，这一阶段要明白的问题：<br>

*今天了解比较透彻*

* HTML是什么， HTML5是什么？
  * HTML <br>
    超文本标记语言，标记语言是一套标签，HTML使用标签描述网页
  * HTML5 <br>
    HTML、XHTML 以及 HTML DOM 的新标准，由W3C与WHATWG合作制定
    
* HTML元素标签、属性都是什么概念？ <br>
  HTML页面是由标签组成的，标签包围的是HTML元素，每个标签拥有自己的属性
  
* 文档类型是什么概念，起什么作用？ <br>
  DOCTYPE，表明web制作过程中用的HTML或XHTML类型，用来提示浏览器或其他阅读程序按照什么规则集去解释文档标记。
  
* 链接是什么概念，对应什么标签？ <br>
  网页里的链接主要是内容之间的跳转，可以是页面内的，也可以是页面外部的，对应‘<a>’标签。
 
* ol, ul, li, dl, dd, dt等这些标签都适合用在什么地方，举个例子？ <br>
  列表标签，例如网页导航；在文档要分层的时候，像这个READNE用HTML表现就会用到。
  
*需要后续继续深入阅读*

* meta标签都用来做什么？ <br>
  提供页面的元信息，通过‘name、content’属性给页面添加关键词啊，表明作者，页面简介等；还可以通过这个属性设置自适应屏幕<br>
  ‘http-equiv、content’属性指示传送给服务器的文档头部信息。
  
* 常用标签都有哪些，都适合用在什么场景？ <br>
  一般用的多的： <br>
  布局划分：header,section,div,nav,footer <br>
  文档格式：h1-h6,p,a,span <br>
  有序列表、无序列表、自定义列表：ul,ol,li,dl,dt,dd <br>
  表格：table,tr,th,td 
  
* 表单标签都有哪些，对应着什么功能，都有哪些属性？ <br>
  表单form里的标签，input，select/option，textarea； <br>
  input通过type值来调整功能（文本框，密码框，单选/多选按钮，图片按钮...）<br>
  select是下拉列表，option是列表值 <br>
  textarea文本域，rows,cols属性值决定大小；<br>
  最多的表单标签属性还是name,value用来与js编码或后台交互。
  
*使用次数不足，需要多次使用来解答疑惑*  
* Web语义化是什么，是为了解决什么问题？ <br>
  让机器的理解能力越来越接近人类，代码通过改进后的HTML标准让更多机器能快速解析网页功能。
***
### 第三堂课 2019/7/19
  （学习时长：3h）<br>
给简历添加样式<br>

*今天了解比较透彻*

* 什么是CSS，CSS是如何工作的？ <br>
  层叠样式表，样式定义如何显示 HTML 元素；工作过程<br>
  1. 处理HTML标记并构建DOM树
  2. 处理css标记并构建CSSOM树
  3. 将DOM与CSSOM合并成一个渲染树
  4. 根据渲染树来布局，以计算每个节点的几何信息
  5. 将各个节点绘制到屏幕上
  
* CSS的基本语法是怎样的？ <br>
  CSS 规则由两个主要的部分构成：选择器，以及一条或多条声明。每条声明由一个属性和一个值组成。
  
*需要后续继续深入阅读* 

* CSS选择器是什么概念，简单选择器和属性选择器是什么？ <br>
css选择器使得每一个HTML语句与css样式相对应。<br>
简单选择器就是通过元素、class、id进行匹配，包括通用选择器（\*）<br>
属性选择器：用(\[\])来标记，是一种特殊类型的选择器，他根据元素的属性和属性值来匹配元素

* 文本样式都有哪些相关属性，对应哪些值？ <br>
  * color  颜色
  * font-family  字体
  * font-style  是否是斜体
  * font-weight  用来表现文字粗细
  * font-size  文字大小
  * text-align  对齐方式（左中右）
  * text-decoration  添加上/下划线、删除线
  * text-indent  段落首行缩进
  * line-height  行高
  * text-shadow  文本阴影（三个位置值一个颜色）
***
### 第四堂课 2019/7/20
  （学习时长：2h）<br>
完善简历样式，理解更复杂的选择器 <br>
  
*今天了解比较透彻*
  
* 背景，边框，列表，链接相关属性 <br>
  背景（background，background-color，background-image，background-repeat，background-position）<br>
  边框（border，border-color，border-style，border-width，border的上下左右）<br>
  列表（list-style，list-style-type，list-style-image）<br>
  链接（a:link，a:visited，a:hover，a:active）<br>
  
*需要后续继续深入阅读* 
  
* CSS 各种选择器的概念，使用方法及使用场景CSS / 选择器的优先级<br>
[层叠和继承](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/Introduction_to_CSS/Cascade_and_inheritance)
***
### 第五堂课 2019/7/21
  （学习时长：6h）<br>
三种简历（不同样式） <br>
完成结果：[三种简历](https://philtiger.github.io/Baidu_webcollege_student-demo/three_style/resume.html)
  
*今天了解比较透彻*
  
* 盒模型的概念 <br>
  由margin，border，padding，内容组成的一块叫盒模型。
  
* inline、block和inline-block的概念 <br>
  * 块盒(block box)是被定义为堆放在其它盒子之上的盒子（即盒子之前以及之后的内容出现在不同的行上），<br>
    并且可以给它设置高度和宽度。上面所述的整个盒模型都适用于块盒。
  * 行内盒（inline box）与块盒相反：它跟随文档的文本流堆放（即，它会与周围的文本和其它行内元素出现在同一行，<br>
    并且其内容会像段落中的文本行一样，随着文本流换行）。宽度和高度设置对行内盒无效；在行内盒上的所有内边距、<br>
    外边距和边界设置会改变周围文本的位置，但是不会影响周围块盒的位置。 
  * 行内块盒（inline-block box）介于前两者之间： 它会像行内盒一样，跟随周围的文本流堆放，不会在其前后创建换行；<br>
    不过，它可以像块盒一样，使用宽度和高度设置大小，并且维护其块完整性 — 它不会跨段落行换行（对于一行文本容纳不下的行内盒，<br>
    会落到第二行上，因为第一行上没有足够的空间容纳它，并且不会跨两行换行）。
    
*需要后续继续深入阅读*

* 内外边距，宽度，高度，box-sizing等属性 <br>
  根据box-sizing属性不同，盒模型对应的宽高设置有所不同。
* 浮动，清除浮动
  float,通过父元素清除浮动，clear清除浮动，伪元素方法。
* 如何使用浮动进行布局  
  实现左右分布布局……

