# antiDouYinBurn

抖音 烧屏 遮挡 app Android

屏幕被抖音加号烧了一点，生气简单写了个app 半夜写的，功能一般，凑合用吧

心情好的话可能加点功能，代码太丑而且也简单，不贴了 上边apk或者右边release直接用吧。

V1.1版本：功能简单 只有上下条但是已经挺好用了

V1.2版本：多了右边遮挡，功能也稍微多了点，换屏挺贵的，有迹象的还是用2吧~~~~

觉得好用的话给个star呗~

---------------

食用方法：

V1.2：大部分同1.1

   差异：所有条幅（上下右）点击后隐藏5秒显示（可配），点击左右下角全部关闭（区域宽度可配），可配置是否自动启动抖音（方便tasker用户）

V1.1：刚进去悬浮窗权限给下，如果允许悬浮窗列表还找不到本应用就强退重新进下。

给权限之后 以后就能直接能当启动器用了（直接用这个图标就行不用再从抖音图标进了）。

点上边黑条上边黑条消失，点下边的两个都消失。长按上边黑条可以自定义高度，目前设置不可以超过500像素

如果消失了还想再还原遮挡，可以从多任务里再进一下这个应用。

PS：可以考虑常驻到后台，方便一些。

---------------

今天发现右边的屏幕也有非常轻微的痕迹了右边遮挡迫在眉睫。

-----------------
更新日志：

V1.2：带右遮挡条，屏挺贵的用这个

1.添加右侧遮挡条，宽度，距离上下高度，长度可配
2.每一个边边都做成 点击暂时消失，秒数可配
3.配置页面值显示
4.下条幅变更，点击暂时消失，秒数同右侧
5.全部消失后直接退出
6.全部消失的功能做在点击 左右下角 距离边缘宽度可配
7.添加自动跳转开关，可以配合一些tasker之类的用。


V1.1：上下遮挡条简单版，如果右边没烧屏可以考虑用这个

修复锁屏后anr

V1.0：

优化后台常驻体验。

当次生命周期只读写条幅高度一次

优化设置页面逻辑，现在无论退出还是home再回来都不会是设置页面了

更改设置页面入口为长按上条幅。

下调福长按事件拦截。因为有些抖音需要拖动进度条。

首屏设置为黑背景减少闪屏，提高体验。
