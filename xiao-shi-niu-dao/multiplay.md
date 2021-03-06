# MultiPlay

> ~~咪啪 磨皮~~

2008-06-03加入到osu! Public Release b335版本中的游戏模式，提供了8人同时在一张由房主决定的谱面中进行游戏的模式，简称MP。

mp让玩家可以交换自己喜欢的图和歌，同时带来了玩家之间的直接对抗，能够比pp和排名更加直观看出玩家的强弱，具有一定竞技性，也成为了osu!赛事的基础。

## 竞技模式

* Head to Head
  * 每个人单独计分，打完一张图之后按分数排行
  * 该模式下任何玩家fail都不影响该图的进行
* Team vs
  * 红vs蓝两队进行对抗，打完一张图后比较总分
  * 用于各种赛事
  * 该模式下如果有一整组都进入fail状态则直接结束，fail的组判定失败
* Tag coop
  * 每个人代表一种combo颜色，轮流打一张图的每个部分
  * 如果有一个人fail则直接结束
  * 不计入rank成绩
* Tag Team vs
  * 红蓝两队分别进行 Tag coop模式，打完后进行总分比较
  * 某队中有一人fail则直接结束，fail的组判定失败
  * 不计入rank成绩

## 胜利条件

胜利条件将替换上述的“分数”

* Score
* Accuracy
* Combo
* Score V2

（见名词解释词条\)

### 注意事项

* 请不要选自己不能打的图，尤其是看到排名较高的玩家时，他们并没有义务为你表演难图。
* 下图很慢可以使用分流镜像，耽误别人时间很不好。
* 礼貌言行是交流的基本。

## 常用指令

* 建立房间的人可以在房间的聊天窗口输入以下指令使用。使用!mp addref username可以使该玩家也能使用指令。

| 指令 | 效果 |
| :--- | :--- |
| !mp start n | 用于在n秒后开始游戏。不输入数字（!mp start）即直接开始。在房间里只有一个人的情况下也可以开始游戏。 |
| !mp abort | 用于中断比赛。多在开始/结束时因为有玩家网络中断而造成其他玩家出现“等待其他玩家开始/完成"提示却久久无法开始/结算时使用。 |
| !mp map bid | 用于选图。 |
| !mp addref username | 使不是房间建立者的玩家也能使用指令。（可以用在两人mp但两人网络都不怎么好时互相mp abort。） |
| !mp host username | 用于更换房主。可以在遇到有人有事挂机一段时间但一不小心把房主给了该玩家的情况下使用。 |
| !mp kick username | 用于将该玩家踢出房间。 |
| !mp team username color | 用于在team vs模式下更改该玩家的所属队伍。color一般为blue/red。 |
| !mp move username slot | 用于将该玩家移动到房间的特定位置。 |
| !mp timer n | 计时n秒。 |
| !mp invite username | 邀请该玩家进入房间。 |

