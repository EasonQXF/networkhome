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
一个简单的平移，是我开始对这个感兴趣的开始！
<!--more-->
## SVG的平移

<svg>
<rect x="50" y="50" width="100" height="50">
<animate attributeType="XML" attributeName="x" 
from="50" to="300" dur="3s" begin="1s"
restart="always" repeatCount="3">
</animate>
</rect>
</svg>
- (attributeType：变化的类型，是HTML还是css)
- 创建一个SVG图形，设定好x，y两个坐标，再设定往哪个轴移动attributeName，再设定from、to既可以设定起始和结束坐标，还有添加过程的时间dur、开始前的时间begin、restart、repeatCount等即可以完成SVG图片的平移动画。
- 你学会了吗？赶紧尝试一下吧！
- 实践才能出真知。
- 我在做这个的时候因为代码忘记加上结束</svg>，导致不断尝试不断查资料，最后仔细检查才修改正确。吸取教训，基础知识要牢记，多动手练习。