# day02

### HTML是什么，HTML5是什么

超文本标记语言，HTML5 是对 HTML 第五次修改

### HTML元素标签、属性都是什么概念？

```html
<p>你好啊</p> 
<!--以上整体就是一个元素，而用 <> 包起来的就是标签-->
<div class="wrapper">
</div>
<!--class中的就是属性-->
```



### 文档类型是什么概念，起什么作用？

DOCTYPE 用来说明所使用的 html 类型，告知浏览器按什么规则来进行解释文档标记。

### meta标签都用来做什么的？

> The **HTML <meta> element** represents [metadata](https://developer.mozilla.org/en-US/docs/Glossary/Metadata) that cannot be represented by other HTML meta-related elements, like [``](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/base), [``](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link), [``](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script), [``](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/style) or [``](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title).

针对搜索引擎和更新频度的描述和关键词。

### Web语义化是什么，是为了解决什么问题

语义网是让机器可以理解数据。[如何理解 Web 语义化？](https://www.zhihu.com/question/20455165)

### 链接是什么概念，对应什么标签？

它可以实现从一个网页到另一个网页的跳转，或者从页面的一个位置跳转到另一个位置，还可以从一个网站跳转到另外一个网站。`<a>`

### [常用标签都有哪些，都适合用在什么场景](https://leohxj.gitbooks.io/front-end-database/html-and-css-basic/common-tag.html)

### 表单标签都有哪些，对应着什么功能，都有哪些属性

`<input>`

（1）文本框：<input type="text">
（2）密码框：<input type="password">
 【专有属性】
​         maxlength：限制输入的字符数，取值：数字
​         readonly：设置文本控件只读
（3）单选按钮：<input type="radio">
（4）复选框：<input type="checkbox">
【专有属性】
​         checked，设置默认被选中
（5）提交按钮：<input type="submit">
（6）重置按钮：<input type="reset">
（7）普通按钮：<input type="button">
（8）图片按钮：<input type="image" src=""> 
（9）隐藏域：<input type="hidden">
（10）文件选择框：<input type="file">作者：melody瓶子链接：https://www.jianshu.com/p/57cecb7cfc4c來源：简书著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。



action {URL}：一个URL地址；指定form表单向何处发送数据。

enctype {string}：规定在发送表单数据之前，如何对表单数据进行编码。

指定的值有：application/x-www-form-urlencoded ：在发送前编码所有字符（默认为此方式）；

multipart/form-data ：不对字符编码。使用包含文件**上传控件**的表单时，必须使用该值method {get/post}：指定表单以何种方式发送到指定的页面。

指定的值有：get ：form表单里所填的值，附加在action指定的URL后面，做为URL链接而传递。post ：form表单里所填的值，附加在HTML Headers上。

### ol, ul, li, dl, dd, dt等这些标签都适合用在什么地方，举个例子

有序 ol > li

无序 ul > li

自定义 dl > dt > dd