# 用原生js模仿《锋利的jQuery》第八章：打造个性网站

第一次完成的比较完整的一个项目，断断续续做了一个多星期，包括两个网页——首页和详情页.如下图：  

首页：[戳我浏览](https://yangpeijia.github.io/a-clone-of-shopping-website/copy-index.html)

![image](https://github.com/yangpeijia/a-clone-of-shopping-website/blob/master/index.png)  

详情页：[戳我浏览](https://yangpeijia.github.io/a-clone-of-shopping-website/copy-detail.html)

![image](https://github.com/yangpeijia/a-clone-of-shopping-website/blob/master/detail.png)
***
书里的交互都是用jQuery,这里仿照jQuery的思路全部用原生js写了一遍，包括:  
搜索框文字效果、网页换肤、导航效果、广告效果、最新动态模块内容添加超链接提示、品牌活动横向滚动效果、产品图片放大镜效果、产品图片遮罩层效果、产品小图片切换大图效果、属性介绍之类的选项卡、产品颜色切换、产品尺寸切换、产品数量和价格联动、产品评分效果、放入购物车。
***
写完之后很赞同网友所说的“jQuery能让程序员多活几年”的说法。
***
书中用了很多jQuery插件，这对用原生js去实现是不少的挑战，有时几乎是一天卡一次效果，解决的过程使用程序员三件宝：read-search-ask.
***
通过这个项目的制作，对html、css和js有了进一步的了解，总结了一定的经验。例如：  
1.CSS3 transition大法好；  
2.当添加多个事件处理程序时，DOM2级比DOM0好用。  
3.用ES6的let语法可以解决遍历时的作用域问题，但不是所有浏览器都兼容，所以一开始用ES6写的一些代码块后面还是改回了ES5语法，这里使用了闭包代替。  




