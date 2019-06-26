---
layout: page
title: 弹性布局+响应式图片
excerpt_separator: "<!--more-->"
date: 2019-06-26
categories:
     - 课堂笔记

---
弹性布局？响应式图片？有什么用？好玩吗？
<!--more-->
&nbsp;
## 先来谈谈弹性布局
Flexible Layout
### 弹性布局的布局技术
- 常用的属性有：
1. flex-direction:用来改变主轴方向
2. flex-wrap:用来改变侧轴方向和自动换行
3. flex:flex-grow\flex-shrink\flex-basis三者的缩写
4. 想了解更多可以上[W3CSchool这个网站了解更多](https://www.w3cschool.cn/)
## 弹性布局加上响应式图片的效果那是极好的。
话不多说，我们赶紧来看看效果！调整浏览器大小查看效果。
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
div {
    width: 100%;
    height: 400px;
    background-image: url('/assets/images/banner.jpg');
    background-repeat: no-repeat;
    background-size: contain;
    border: 1px solid red;
}
</style>
</head>
<body>
<div></div>
</body>
</html>
- 弹性布局加上响应式图片的技巧是现在只做网页必须的，毕竟现在不同的设备太多，想要更容易被大众接受，有更好的用户体验这是必须的。所以我们需要这样的技术。
- 抓紧时间练习！多多动手实践才能学到东西，做出更好的网页！
