# Html_JS_CSS_Study
前端学习

1.VSCode**安装**：选择附加任务部分全部勾选、

**2.VSCode扩展：**

Chinese(Simplified)：汉化

HTML CSS support：写CSS代码快捷神器

Live Server:实时预览页面变化效果

Auto Rename Tag：在修改HTML标签的时候，同步修改与之匹配的另一个标签(即修改开始标签，结束标签也自动修改)

**3.HTML**

超文本标记语言：通过一系列标签来定义哪些是标题，哪些是段落，哪些列表，哪些是图像等等

标签成对出现的，双标签：包括开始和结束标签，内容则位于开始标签和结束标签之内。用于有内容的元素。

```html
<P>这是一个段落</P>
<h1>
    这是一个一级标题
</h1>
<a href="#">这是一个超链接</a>
```

单标签:用于**没有内容的元素**。

```html
<input type="text">
<br> 换行标签
<hr> 分隔线标签
```

**HTML文件结构**

```html
<!DOCTYPYE html> 告诉浏览器这是一个HTML文件
<html>
	<head> 文档的头部：包含了文档元信息
        <title>文档标题</title>
        <meta chatset="UTF-8"> 文档编码格式
        <!-- 连接外部样式表成脚本文件等-->
        <link rel="stylesheet" type="text/css" href="styles.css">
        <script src="script.js"></script>
    </head>
    <body> 显示在浏览器页面的内容，文本图像联接等
		<h1>
            这是一级标题
        </h1>        
        <p>
            这是一个段落
        </p>
        <a href="https//www.example.com">这是一个链接</a>
    </body>
</html>
```

**快捷**打开：进入C:\Users\48467\Desktop\Html_JS_CSS_Study，输入cmd,再输入code .就可以打开该项目的vscode

在vscode中手动搭建html骨架太耗费时间，我们可以在首行输入！，然后选择！，再tab就可生成html文档结构

预览html，代码空白处鼠标右键，open wiht live server,就可以在浏览器中预览页面效果

**HTML属性**

每个标签都可以有一个或者多个属性：用于描述元素的行为外观以及和其他元素的关系

```
基本语法
<开始标签 属性名="属性值">  这里可以是单引号或者双引号
```

每个html元素可有不同的属性

```html
<p id="describe" class="section"> 这是一个段落标签</p>
<a href="https://www.sample.com"> 这是一个超链接</a>
```

属性名称不区分大小写，属性值对大小写敏感

```html
<img src="example.jpg" alt=""> src表示图片标签的路径
<img SRC="example.jpg" alt="">
<img src="Example.jpg" alt="">
12相同，3不同
```

大部分标签都可以使用的属性

```
class:为html元素定义一个或者多个类名（类名从样式文件引入）
id:定义元素唯一的id
style：规定元素的行内样式
```

HTML 区块-块元素与行内元素

```
块元素用于组织和布局页面的主要结构和内容，段落标题列表表格等。
通常从新行开始，占据整行的快读，页面呈现为一块独立的内容快
可以包含其他块级元素和行内元素
常见的块级元素div p h1~h6 ul ol li table form等

行内元素用于添加文本样式或为文本中的一部分应用样式
通常在同一行呈现，不会独占一行
只占据其内容所需宽度，而不是整行的宽度
行内元素不能包含块级元素，但可以包含其他行内元素
常见行内元素 span a strong em img br input
```

创建div块的快捷方式

```html
.liuxinjie或者div.liuxinjie回车 得到
<div class="liuxinjie"></div>

#liuxinjie或者div#liuxinjie 回车 得到
<div id="liuxinjie"></div>
创建div块初始附带id快捷键 
```

CSS 层叠样式表

《3小时前端入门教程》进度123456集











