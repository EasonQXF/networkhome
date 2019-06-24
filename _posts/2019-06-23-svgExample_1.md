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
1.
2.
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