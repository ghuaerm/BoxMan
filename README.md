# 基于C++的推箱子游戏

## 介绍
    本系统是一个基于EGE图形库的C风格C++推箱子游戏，游戏使用mmsystem API播放音效，共35关，完美还原经典关卡。			
    在游戏主界面中，会出现一个小人、若干个箱子和箱子放置点。玩家需要利用方向键控制小人上下左右移动，并推动界面中的箱子到达指定的箱子放置点。

## 推箱子和地图编辑器


[/output/BoxMan.exe][game]：编译好的程序，Windows下可直接运行

[/output/BoxManEditer.exe][editor]：地图编辑器，可以对地图进行修改或添加

### 效果截图

* EXE运行

 ![游戏截图](https://github.com/ghuaerm/BoxMan/blob/master/image/8.png)
 
* 地图编辑器

 ![地图编辑](https://github.com/ghuaerm/BoxMan/blob/master/image/9.png)

### 程序运行测试
+ 程序启动后，其菜单及游戏如图所示。

 ![游戏](https://github.com/ghuaerm/BoxMan/blob/master/image/1.png)

 ### 键盘操作功能测试，测试步骤如下。
+ 游戏开始后按下‘S’键进入开始菜单界面，如图所示。

 ![游戏](https://github.com/ghuaerm/BoxMan/blob/master/image/2.png)
+ 玩家可以选择‘A’键从头开始闯关，直接进入游戏界面，也可选择‘X’键手动选择关卡。按下‘R’键返回主菜单。如图所示。

 ![游戏](https://github.com/ghuaerm/BoxMan/blob/master/image/3.png)
+ 玩家可以选择‘W’键和‘S’键进行关卡的选择，按下‘R’键返回开始菜单界面。选择关卡之后按下‘ENTER’键进入游戏。如图所示

 ![游戏](https://github.com/ghuaerm/BoxMan/blob/master/image/4.png)

+ 单击键盘上的方向按键，来控制主角移动，在箱子移动到目标位置时变色。

 ![游戏](https://github.com/ghuaerm/BoxMan/blob/master/image/6.png)
+ 暂停游戏并测试继续（R），选关（X），重玩（Q），下一关（N），菜单（M）分别进行测试。

 ![游戏](https://github.com/ghuaerm/BoxMan/blob/master/image/5.png)

### 测试推箱子游戏中游戏胜负判断功能
 ![游戏](https://github.com/ghuaerm/BoxMan/blob/master/image/5.png)

