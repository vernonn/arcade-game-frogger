经典街机游戏，青蛙过河类游戏
=======

## <i class="icon-list"></i> 本页索引
* [快速游戏](#快速游戏)
* [游戏介绍](#游戏介绍)
* [操作方式](#操作方式)
* [TodoList](TodoList)

## 快速游戏

[记忆游戏（点击进入游戏页面）](https://www.vernonn.com/udacity/project-two/index)

## 游戏介绍
- 游戏页面打开**自动开始**游戏。
- 游戏界面很简单，横向6行，竖向5列；横向来看，从上到下分别为：
    - **河流** *（最终目的地，安全地带）*
    - **四行石板路** *（视为青蛙过河游戏里青蛙需要穿越的河道，有敌人横穿而过，危险地带）*
    - **草地** *（玩家角色初始位置，安全地带）*

- 游戏内的敌人是一只只**甲虫**，分别以不同的速度穿行在**四条石板路**上；本游戏默认设置游戏界面内共存**5**只甲虫。
- 当玩家角色（视觉上）碰撞到**甲虫**，则返回草地安全区*（竖向坐标初始化，横向坐标不变）*。
- 当玩家角色到达**河流安全区**，则视为**游戏过关**！届时会有游戏完成的面板弹出，仅作提示，可以点击面板内的“再玩一次”按钮来再次进行新一轮游戏。

## 操作方式
本游戏操作简单，可使用键盘的上下左右键进行控制。
也可以用WASD进行控制：A代表向左移动一格，D代表向右移动一格W代表向上移动一格，S代表向下移动一格。

## TodoList
- [x] 简单游戏规则实现
- [ ] 添加过关限时
- [ ] 添加玩家角色血量（例如3滴血，每碰撞一次失去一滴血，当血消耗完，则游戏失败）
- [ ] 添加游戏失败提示栏
- [ ] 添加玩家角色形象选择功能
- [ ] 添加石头障碍物（对玩家可形成障碍，对甲虫无影响）

>>>>>>> 当前版本 1.0.0
