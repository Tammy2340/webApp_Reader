# webApp书城整站开发
<p>由Koa、Vue、Zepto等框架结合HTML5开发的一个具有阅读器功能的书城App，将整个过程分为三个主要模块进行开发，分别是阅读器、书城整站和搜索模块。</p>
#<h2>目录</h2>
<ul>
<li>mock: 模拟数据,充当数据库的作用</li>
<li>service: 读取数据,充当前后端的纽带。大部分数据是通过mock读取，少部分真实数据是直接发起http请求去获取</li>
<li>static: 静态资源</li>
<li>view: ejs模板</li>
<li>app.js: 项目入口</li>
<li>package.json: 项目所需依赖</li>
</ul>
<h2>阅读器开发-技术点</h2>
<ul>
<li>使用base64格式图片</li>
<li>使用viewport布局移动端页面</li>
<li>HTML5的localStorage:本地存储，可以存储用户的阅读章节和阅读习惯等</li>
<li>可以跨域的Ajax：发送请求获得数据后渲染UI界面</li>
<li>ES6的Promise对象：用来传递异步操作的消息，充当异步和回调的中介，免除重复繁琐的回调函数嵌套</li>
</ul>
<h2>书城整站开发-技术点</h2>
<ul>
<li>nodejs的环境搭建</li>
<li>npm、koa、vue的使用</li>
<li>EJS模板</li>
</ul>
