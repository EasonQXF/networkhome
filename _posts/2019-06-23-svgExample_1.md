---
layout: page
title: SVG有趣的例子
excerpt_separator: "<!--more-->"
date: 2019-06-23
categories:
     - SVG制作
tags:
  - svg

---
SVG+CSS3动画

<!--more-->
## SVG有趣的例子
- 颜色会渐变
<head>
  <meta charset="UTF-8">
<style> 
.QXF
{
width:100px;
height:100px;
background:red;
animation:QXF 5s;
animation-iteration-count: infinite;
}

@keyframes QXF
{
from {background:red;}
to {background:blue;}
}



</style>
</head>
<body>

<div class="QXF"></div>
</body>


- 不仅会渐变，还会移动
<head>
<style> 
div
{
width:100px;
height:100px;
background:red;
position:relative;
animation:aaa 5s linear 2s infinite alternate;


@keyframes aaa
{
0%   {background:red; left:0px; top:0px;}
25%  {background:green; left:200px; top:0px;}
50%  {background:yellow; left:200px; top:200px;}
75%  {background:black; left:0px; top:200px;}
100% {background:red; left:0px; top:0px;}
}
</style>
</head>
<body>
<div>动起来</div>

</body>