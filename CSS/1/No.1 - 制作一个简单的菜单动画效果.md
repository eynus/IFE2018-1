# No.1 - 制作一个简单的菜单动画效果

[预览]()
##　学习资料

- [MDN transitions](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions)
- [CSS3 新特性兼容方法总结](https://www.cnblogs.com/jesse131/p/5441199.html)
- [Understanding CSS3 Transitions](http://alistapart.com/article/understanding-css3-transitions)
- [动效落地方法](https://zhuanlan.zhihu.com/uxelement)
- [优秀的 CSS 交互动效示例](https://lab.hakim.se/ladda/)

> 优秀的界面动效体系符合以下四点原则：
>
> 1. **通过动效暗示二维界面暗含的三维层级关系，及其暗含的操作逻辑**
> 2. **引导用户的注意力向界面重点元素**
> 3. **通过动态设计让情感化设计变得更生动**
> 4. **动效的视觉效果统一，控制数量，不滥用**

## 大概思路

在字体下放一个块，从中间往外的运动，宽度居中，宽度从 0 到 100%
给该块一个 active 样式, js 操纵 active 即可

