---
layout: page
title: SVG的文本移动
excerpt_separator: "<!--more-->"
date: 2019-06-25
categories:
     - SVG制作
tags:
  - svg

---

<!--more-->
## SVG的文本移动
下面是superman这个单词沿着一条带拐弯的路径移动。

<svg width="640" height="480" version="1.1">
<g transform="translate(150,150)">
<path d="M0,0 L70,70 L150,270 L-230,-470" style="fill:restart;stroke:red;stroke-width:2"/>
<text x="0" y="0" font-size="37" visibility="hidden"
stroke="red" stroke-width="2">
Superman
<set attributeName="visibility"
attributeType="CSS" to="visible"
begin="1s" dur="5s" fill="freeze"/>
<animateMotion path="M0,0 L70,70 L150,270 L-230,-470"
begin="0.5s" dur="10s" fill="restart" rotate="auto"/>
</text>
</g>
</svg>

- 这个例子是老师在课堂上展示过给我们看的，课后我回去将其修改成上面所示那样。
- 我们先使用了<set>元素，使得superman能够显示出来，并且沿着路径移动。时间设置为5s和10s。设置"rotate"属性为"auto"，使Superman到了拐弯的地方时继续紧贴着路径前进，而不是维持原来的方向："fill"属性设置为"restart"，表示动画播放完毕后，就恢复原来的画面状态。
- path是路径的数据，通过空格和逗号进行路径数据的改变改变文字的走向。
> 代码可供尝试，删除了部分导致显示不完全的代码:
1. <svg width="640" height="480" version="1.1"
2. g transform="translate(150,150)">
3. path d="M0,0 L70,70 L150,270 L-230,-470" style="fill:restart;stroke:red;stroke-width:2"/>
4. <text x="0" y="0" font-size="37" visibility="hidden"
5. stroke="red" stroke-width="2">
6. Superman
7. <set attributeName="visibility"
8. attributeType="CSS" to="visible"
9. begin="1s" dur="5s" fill="freeze"/>
10. <animateMotion path="M0,0 L70,70 L150,270 L-230,-470"
11. begin="0.5s" dur="10s" fill="restart" rotate="auto"/>
