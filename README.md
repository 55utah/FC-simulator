# FC-simulator
> 用go实现一个小霸王/NES/FC/红白机模拟器
### 支持情况
已支持mapper0/1/2/3/4的游戏，如冒险岛/沙曼陀蛇/魂斗罗/超级马里奥等大部分常见游戏
### 音效
支持音效
### GUI
选择了fyne.io
### 桌面版使用方式
源码
`go run main.go /User/xxx/xxx.nes`
二进制文件
`./main /User/xxx/xxx.nes`
### 桌面版操作
```
系统按键:
Q   重置游戏
-   缩小画面
=   放大画面

手柄1:
W/S/A/D  上下左右
F/G   游戏A/B键
R/T  选择/暂停

手柄2:
方向键  上下左右
J/K  游戏A/B键
U/I  选择/暂停
```
### 效果展示

<img src="https://user-images.githubusercontent.com/17704150/147229324-08580103-be82-4d53-8538-a989b95bb7df.gif" width="200">
<img src="https://user-images.githubusercontent.com/17704150/147230553-55e57fbc-c0c5-4eb5-9fa1-7bc15af480d8.gif" width="200">
