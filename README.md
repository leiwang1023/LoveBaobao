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
 插入超链接，href="网址",默认在当前页面打开，除非指定target 属性 e.g. 连接到公共网页：\<a href="https://github.com/" target="_blank">不要点这个个链接\</a>;连接到本文件夹网页 \<a href="./ff1/index.html" target="_blank">不要点这个个链接\</a>
 9. \<canvas>\</ canvas>
 定义一个图形容器，图形必须使用脚本来绘制
 10. \<script>\</ script>
 在HTML 页面中插入一段javascript
 11. js setTimeout
 settimeout(执行的代码和函数, 等待的毫秒数)
 12. js setInterval
 周期执行函数 setInterval(code, 执行周期)
 13. \<meta>
 在head 中，元数据，会被解析指定加载网页的一些属性和说明
  \<meta http-equiv="content-type|default-style|refresh"> 指定字符集/预定义的样式表/自动刷新时间
  14. \<style>\</ style>
  head 中，如何呈现html 文档，type 属性必须的，唯一值为 "text/css"
  @font-face 自定义字体
  15. \<link />
  head 中，定义文档与外部资源的关系，最常见的用途是链接样式表
  16. css 样式
   - margin: 外边距
   - padding: 填充
   - background: 颜色/图像/重复(平铺)/固定、滚动/起始位置
   - font: family/size/style/variant/weight
   - overflow: 内容溢出
   - float: 元素块左右浮动