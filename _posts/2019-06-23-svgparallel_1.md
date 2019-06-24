---
layout: page
title: SVG的平移
excerpt_separator: "<!--more-->"
date: 2019-06-23
categories:
     - SVG制作
tags:
  - svg

---

<!--more-->
## SVG的平移
<head>
  <meta charset="UTF-8">
<style> 
.ping
{
width:100px;
height500px;
background:white;
animation:ping 5s;
animation-iteration-count: infinite;
attributeName="x";
dur="4s";
begin="1s";
}

@keyframes ping
{
From="50";
to="300";
}
</style>
</head>
<body>

<div class="ping"></div>
</body>

- (attributeType：变化的类型，是HTML还是css)
- 创建一个SVG图形，设定好x，y两个坐标，再设定往哪个轴移动attributeName，再设定from、to既可以设定起始和结束坐标，还有添加过程的时间dur、开始前的时间begin、restart、repeatCount等即可以完成SVG图片的平移动画。
