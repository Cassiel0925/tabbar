## TabBar 的实现思路

1. 创建tabbar vuecli2

![](D:\大四上\Vuejs\tabbar实现思路\images\vuecli2初始化tabbar.png)

2.  大致思路

![](D:\大四上\Vuejs\tabbar实现思路\images\大致思路.png)

3. tarbar 基本结构的搭建

![](D:\大四上\Vuejs\tabbar实现思路\images\初稿.png)

![](D:\大四上\Vuejs\tabbar实现思路\images\tabbar基本架构的ui.png)

4. tabbar - TabBar 组件封装

第一步：

![](D:\大四上\Vuejs\tabbar实现思路\images\封装tabBar组件.png)

针对某一个功能单独创建一个文件夹 这个文件夹封装这个组件相关功能的文件

第二步： 使用iconmoon

![](D:\大四上\Vuejs\tabbar实现思路\images\icon moon的使用.png)

第三步： 封装 TabBarItem 组件

![](D:\大四上\Vuejs\tabbar实现思路\images\TabBarItem的封装.png)

第四步：活跃状态的操作 给TabBarItem 传入 active图片

![](D:\大四上\Vuejs\tabbar实现思路\images\活跃状态的操作.png)

第五步： TabBarItem 和 路由结合效果

![](D:\大四上\Vuejs\tabbar实现思路\images\route的使用.png)

第六步： TabBarItem 颜色动态控制

![](D:\大四上\Vuejs\tabbar实现思路\images\颜色的动态控制.png)

第七步：抽取组件MainTabBar

![](D:\大四上\Vuejs\tabbar实现思路\images\抽取MainTabBar.png)