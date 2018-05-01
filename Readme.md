<li>Markdown 支持两种标题的语法，Setext 和 atx 形式。Setext 形式是用底线的形式，利用 = （最高阶标题）和 - （第二阶标题），Atx 形式在行首插入 1 到 6 个 # ，对应到标题 1 到 6 阶。
区块引用则使用 email 形式的 '>' 角括号。




<li>无序列表使用星号、加号和减号来做为列表的项目标记，这些符号是都可以使用的，<br>使用星号：<br>* Candy.
* Gum.
* Booze.<br>
加号：<br>
+ Candy.
+ Gum.
+ Booze.
<br>和减号<br>
- Candy.
- Gum.
- Booze.
都会输出 HTML 为：
<ul>
<li>Candy.</li>
<li>Gum.</li>
<li>Booze.</li>
</ul>
有序的列表则是使用一般的数字接着一个英文句点作为项目标记：
1. Red
2. Green
3. Blue
<br>Markdown 支援两种形式的链接语法：
行内形式是直接在后面用括号直接接上链接：<br>
This is an [example link](https://www.baidu.com/).
<br><li>图片<br>
图片的语法和链接很像。<br>
行内形式（title 是选择性的）：<br>
![alt text](C:\Users\Dell\Desktop\cquptmap\ditu2.0\css\xxm.jpg)<br>
<img src="xxm.jpg">
参考形式：<br>
[id]: /path/to/img.jpg "Title"
上面两种方法都会输出 HTML 为：
<img src="/path/to/img.jpg" alt="alt text" title="Title" />
<br><li>代码
在一般的段落文字中，你可以使用反引号 ` 来标记代码区段，区段内的 &、< 和 > 都会被自动的转换成 HTML 实体