# 什么是语义化？语义化的手段都有哪些？

* 语义化是指用合理HTML标记以及其特有的属性去格式化文档内容。通俗地讲,语义化就是对数据和信息进行处理,使得机器可以理解.
* 语义化的(X)HTML文档有助于提升你的网站对访客的易用性，比如使用PDA、文字浏览器以及残障人士将从中受益。对于搜索引擎或者爬虫软件来说，则有助于它们建立索引，并可能给予一个较高的权值。
* 事实上SEO最有效的一种办法，就是对网页的HTML结构进行重构，实质上就是语义化。
* HTML语义化就是**根据内容，选择合适的html标签**，写出:
  1 便于开发者阅读和代码美观
  2 利用机器爬虫解析的代码
* 能够让你更恰当的描述内容是什么


* 手段

1 尽量减少无意义的标签，比如div span

2 语义不明显的时候，使用<p>要好于<div>

3 不要使用纯样式标签，比如<b><i> 表示强调时要用语义标签<strong><em>代替

4 使用表格时要用<caption><thead><tbody><tfoot>等，使表格语义化

5 表单域要用<fieldset>包裹起来，并用<legend>说明他的用处