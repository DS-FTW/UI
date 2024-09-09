## Font 家族
| field           | Value                           | desc                            |
| --------------- | ------------------------------- | ------------------------------- |
| font-family     | 'Times New Roman', Times, serif | 根据顺序找，找不到使用默认      |
| font-size       | 16px                            |                                 |
| font-weight     | 400                             | 400(normal)700(bold)            |
| font-style      | normal                          | italic 斜体                     |
| color           | rgb(255, 0, 255)                | 颜色                            |
| text-align      | right                           | 文本水平对齐                    |
| text-decoration | underline/line-through/none     | 下划线、删除线、取消文本装饰    |
| text-indent     | 2em                             | 缩进                            |
| line-height     | 25px                            | 行间距(行等于div高度表垂直居中) |
## 背景
| field                 | Value                        | desc             |
| --------------------- | ---------------------------- | ---------------- |
| background-color      | red,transparent(透明的)      | 背景颜色         |
| background-image      | url(images/logo.png)         | 背景图片         |
| background-repeat     | repeat/no-repeat             | 背景图片默认平铺 |
| background-position   | center/top/bottom/right/left | 图片对齐方式     |
| background-attachment | fixed                        | 背景图片固定     |
| background            | rgba(0, 0, 0, .3)            | 背景半透明       |
## 背景复合写法
> background: black url(images/bg.jpg) no-repeat fixed center top;
## font 复合写法
> font: font-style  font-weight  font-size/line-height  font-family;
## 选择器
| field           | Value                            | desc                 |
| --------------- | -------------------------------- | -------------------- |
| 标签选择器      | div{}                            |                      |
| class选择器     | .red{} .box{}                    |                      |
| 多类名选择器    | \<div class="box red">           |                      |
| id选择器        | \<div id="box">                  |                      |
| *               | *{}                              | 通配符选择器         |
| 后代选择器      | ol li { color: pink;}            |                      |
| 子元素选择器    | .nav>a {color: red;}             | 仅包含儿子，直系一代 |
| 并集选择器      | div, p, .pig li { color: pink; } | 逗号分隔             |
| 链接伪类选择器  | a:link {}  a:hover{}             |                      |
| focus伪类选择器 | input:focus {}                   | input框获取光标时    |
## 样式
1. 内部样式 
>\<style>
>  div {
>   color: pink;
>       }
> \</style>
2. 行内样式  
>\<p style="color: pink; font-size: 20px;">
3. 外部样式  
>\<link rel="stylesheet" href="****.css> 


## 显示模式
> 块级元素   
>1. \<h1>~\<h6>,\<p>,\<div>,\<ol>\<ul>\<li>  
>2. 独占一行
>3. 宽，高，内外边距，可控制
>4. 默认宽度是父类的100%,高度默认为0
>5. 可以放块和行元素

> 行内元素   
>1. \<a>,\<strong>,\<b>,\<em>,\<i>，\<del>，\<s>,\<ins>,\<u>,\<span>  
>2. 一行可以显示多个
>3. 高宽设置无效
>4. 默认宽度就是它本身内容宽度
>5. 行内元素只能容纳文本和其他行内元素
>6. 高、宽无效，但水平方向的padding和margin可以设置，垂直方向的无效

> 行内块元素  
>1. \<img>，\<input>,\<td> \<button> 
>2. 注意：链接不能放链接
>3. 一行可以显示多个，但是有空隙
>4. 默认宽度就是它本身内容宽度
>5. 高度，行高，宽度，内外边距可控

### 显示模式转换
>1. display: block;
>2. display: inline;
>3. display: inline-block;





