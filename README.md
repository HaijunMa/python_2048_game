# python_2048_game

          开发者：马海军               开发时间：2017/1/6

## 游戏规则：

      游戏的规则很简单，你需要控制所有方块向同一个方向运动，两个相同数字的方块撞在一
      起之后合并成为他们的和，每次操作之后会在空白的方格处随机生成一个2或者4，最终得
      到一个 “2048”的方块就算胜利了。如果格子全部填满并且相邻的格子都不相同也就是无
      法移动的话，那么游戏就结束啦。

## 游戏页面：

      页面一：

![游戏页面](https://github.com/HaijunMa/python_2048_game/blob/master/1.jpg)

      页面二：   
![游戏页面](https://github.com/HaijunMa/python_2048_game/blob/master/2.jpg)

## 高分法则：

    1、最大数尽可能放在角落。

    2、数字按顺序紧邻排列。

    3、首先满足最大数和次大数在的那一列/行是满的。

    4、时刻注意活动较大数（32以上）旁边要有相近的数。

    5、以大数所在的一行为主要移动方向

    6、不要急于“清理桌面”。

       需要注意的是，为了保持最大数在角落，所有最大数可能移动的方向都不能再操作了，比如选择
    了左上角，那么就不能向右和向下移动其他的方块，这样操作的灵活性会相对减少，难度就会增加。
    这时，建议玩家除了选定一个角以外，再固定一条边，将大的数字放这条     边上，这样就可以朝
    三个方向移动，比如选定左上角，填满最大数右边的所有方块，就可以朝上，左，右三个方向移动了。
