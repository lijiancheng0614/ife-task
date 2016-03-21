### 上传说明: 
- 文件命名规则是：日期+标题（如：2015-03-21-task1.html),这样jekyll才能编译
- 每个文件开头加上
<pre><code>
---
layout: post
h1: 文件的名称 (如：task1）
tags: \["作者的昵称",...\]\(当然也可以不写，也可以写多个，用逗号隔开\)
---
</code></pre>
- 图片放在img文件夹，css文件放在css文件夹，js文件放在js文件夹
引用举例，比如我要应用css文件夹中的1.css文件，则:
href="{{site.baseurl}}/css/1.css"
- 文件都上传到gh-paes分支的_posts文件夹下
同时merge到master分支
