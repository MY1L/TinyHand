用于而不限于视窗系统的自制光标系列。

这是对2018年12月9日发布的“[thinkingcursor](https://github.com/MY1L/thinkingcursor)”光标的更新，但改成更好记的名称：**TinyHand**。主要是让动画更流畅（指帧数）及修正某些像素级的错误。如今更支持**黑暗模式**和中指，从一扩大为三系列，政确力UpUp!

## 一览
一共三大系列（肤色）：ZRKL、KOFJI、ANNYUI（名称越长颜色越暗）和各种小分支。

![KOFJI](/_img/KOFJI.gif)

用动图展示包含的几个动画光标。由于GIF最多显示256色，以下就不用动图了。

![ZRKL](/_img/ZRKL.png)

给ZRKL做的手势比较多。注意“sweat.ani”是代替“helpsel.cur”的，动画光标不太宜作常态光标。

![ANNYUI](/_img/ANNYUI.png)

上述两个系列个别光标有透窗效果，而ANNYUI是全部都带透窗效果的黑暗模式，相当于再做了一组。预览图……再给我点时间。

## 更新
* 未来计划：小小手，仅24~16px尺寸的光标如图![TinyTiny](/_img/TinyTinyHand.png)，如有需求就做。
* 2020-2-9 v0.6 修正`cross`。给`Zmidfinger🖕`加了Zanger💢分支，给`Aunavail🚫`加了令和十八年🔞分支。补完ZRKL系列。
> 💢不慎误操作让GitHub删除我今天21个更新，凭记忆重做一遍。
* 2020-2-7 v0.3 修改所有`.inf`文件，现在会自动打开 控制面板→鼠标 了。

## 下载 ![GitHub repo size](https://img.shields.io/github/repo-size/MY1L/TinyHand) ![GitHub All Releases](https://img.shields.io/github/downloads/MY1L/TinyHand/total)
全部打包：[Releases · MY1L/TinyHand](https://github.com/MY1L/TinyHand/releases)

## 安装

### 勤快向
先把光标们放到一个你确定不会动的位置，控制面板→鼠标→指针，创建一个新光标方案逐个改动。这样不会有什么文件倒进系统里。
### 懒人向
对`.inf`右键点“安装”，这会把一堆相关光标一股脑儿全倒进`%SYSTEMROOT%\Cursors\TinyHand`系统光标文件夹里，并在注册表`HKCU\Control Panel\Cursors\Schemes`生成一个光标方案。等复制完（很快的）后会自动打开 控制面板→鼠标，此时应该改好了，如果没变化，选 鼠标→指针→`TinyHand ***`方案，点应用。

如有“你所选择的光标方案名已在使用中。是否要替换原方案?”提示可以无视。

## 卸载
控制面板→鼠标→指针，删除方案，再删除对应光标。如果用的`.inf`安装，还要进系统光标文件夹删`TinyHand`文件夹。

## 注意
* 资源管理器可能会错误地显示光标缩略图，例如发现TinyHand光标出现在TinyHand文件夹之外（这应该不可能），请删除前用控制面板的光标预览确认下。
* 控制面板的指针预览不会按正常速度显示动画光标。
* 中指光标的灵感来自[这个用于百度的脚本](https://greasyfork.org/zh-CN/scripts/28206-baidu-cursor)。
* 可以自行修改`.inf`，但保存时文本编码必须选ANSI，否则安装的方案名会乱码。

若要定制其它题材光标或赞助，[请来这发电](https://afdian.net/@FairyFloss)。

还有其它问题建议就来[Issues ](https://github.com/MY1L/TinyHand/issues)发帖。