[toc]

---
记录下写的第一个网页的的一些东西

----
 1. \<head>\</head>
 标题元素块
 2. \<title>标题\</title>
 在head 中定义head 的title
 3. \<body>\</body>
 文档的主体，包括文档的所有内容，如文本超链接图像表格和列表等
 4. \<div>\</div>
 division/section,把文档分隔为独立的部分，使用id 标记作为标识
 5. \<span>\</span>
 文本标记，拥有id or class，class 可以控制文本样式
 6. \<br>\<br />
 换行符，因为换行符没有开始和结束之别，所以使用<br />表示应用于开头的结束标识
 - <标签 />
 这种形式的标记表示位于开始的结束，如上面的换行符\<br />;\<span class="space" /> 但是建议大多建议使用配对的<></>
 7. &nbsp
 空格的转义字符，一个表示一个空格，而在html 文件中输入多少个空格都只会显示一个
 8. \<a>\</ a>
 插入超链接，href="网址",默认在当前页面打开，除非指定target 属性 e.g. \<a href="https://github.com/" target="_blank">不要点这个个链接\</a>