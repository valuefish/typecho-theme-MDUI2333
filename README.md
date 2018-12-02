# typecho-theme-MDUI2333

基于[MDUI](https://mdui.org)的一款typecho主题，私用为主QAQ……若喜欢可以Star，谢谢QwQ。

作者：ZigZagK | 版本：1.1

## 主题特性

1. 基于[MDUI](https://www.mdui.org/)，结合PJAX。有丰富（拥挤）的侧边栏栏目比如用[tagcanvas](http://www.goat1000.com/tagcanvas.php)实现的标签云。
2. 支持文章头图设置（随机头图来源[typecho-theme-material](https://github.com/viosey/typecho-theme-material/tree/master/img/random)，侵删），评论字数限制，文章访问量统计，热门文章，音乐播放器（By [Aplayer](https://github.com/MoePlayer/APlayer)&[Meting](https://github.com/metowolf/MetingJS)）等功能。
3. 使用[Highlight](https://highlightjs.org/)渲染代码片并资瓷行号显示，[MathJax](https://www.mathjax.org/)渲染`LaTeX`数学公式（毕竟我是个OIer嘛QAQ）。
4. 一点都不丰富的自定义设置。~~（这哪里是特性了）~~
5. 中文最棒啦，所以不支持多语言。高版浏览器最棒啦，所以不兼容低版浏览器。~~（这完全是敷衍吧）~~

## 演示

可以参考[ZigZagK的博客](https://zigzagk.top)（可能需要科学上网TAT）。

## 如何使用

1. 下载之后改名为MDUI2333放入主题目录，之后启动主题。
2. 在设置外观中设置一下主题色强调色，背景图片等。
3. 友情链接页面使用方法：先安装插件[typecho-links-material](https://github.com/idawnlight/typecho-links-material)并添加友情链接。然后创建一个空页面，将模板改为友情链接页面。

## 待填坑

评论无刷新。（对这个一脸懵逼，希望有大佬指点Orz）

## 预览

![](https://raw.githubusercontent.com/ZigZagK/typecho-theme-MDUI2333/master/screenshot.png)

![](https://raw.githubusercontent.com/ZigZagK/typecho-theme-MDUI2333/master/preview.png)

## 版本更新

### 1.1

什么？MDUI只要加一句话就支持移动端了？于是轻松解决了移动端问题（雾）。

优化了一下侧边栏热门文章和最新评论的显示，把`<a>`的`title`属性换掉改成了MDUI的提示框。

优化了一下文章搜索的样式（其实就是去掉了`width:25%`……），增加了下方链接的提示框。

好像不算很大的更新……不过填掉了第一个神坑，还是很开心的QAQ。