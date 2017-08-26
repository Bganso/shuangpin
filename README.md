# 双拼键盘布局 -- 月边鸟
```
-------------------------------------------------------------
| Q   | W   | E     R   | T     Y     U sh| I ch| O     P   |
|     | ao  | e     ei  | ua    uai   u   | i   | o     ou  |
|     |     |           | ia    ue        |     | uo        |
-------     ---         ---               ---   ---------   ---
  | A     S   | D     F   | G     H     J   | K     L   | ;   |
  | a     ai  | en    eng | uan   uang  un  | in    ing | ong |
  |           |       er  |       iang      |           | iong|
  ----        -------------------------------   ---------------
     | Z     X   | C     V zh  B     N     M    |
     | an    ang | ie    u:    ian   iao   iu   |
     |           |       ui                     |
     --------------------------------------------
```
为方便记忆，键盘布局根据韵母的首韵划分为 A E I O U 五个区域。六个根韵母 a e i o u ua 分别对应 A E I O U T 键位。与根韵母相关的其它韵母大致按以下规则分布。
```
    --------------------------
    |           |            |
    | 根韵母     | 根韵母+i或u |
    ----------------------------
      |           |            |
      | 根韵母+n   | 根韵母+ng   |
      --------------------------
```
下面是一些例外情况：

 * 对于 ui，其对应键位已被 i 占据，因此被分配到 V 健位，取谐音之法。
 * ia 和 ua 共享一个键位，但 uan 已占据该键位下方，因此 ian 被分配到更下一行的 B 键位上，可以用 "边" 助记。

需要另外记忆的规则:

 * ao 分在了左上方的 W 键位。
 * 键盘中下方的五个键位都分配给了与 i 相关的韵母，其中 ie 在 e 的所在列，iu 在 u 的所在列。iao 在 N 键位，可以用 "鸟" 助记。
 * er 和 eng 共享 F 键位，uo 在 O 键位，iong 和 ong 共享；键位，都是相似和谐音。
 * ue 在 Y 键位，可以简单地用 "月" 助记。

# Linux 安装

 * 安装 fcitx
 * 拷贝 sp.dat 至 ~/.config/fcitx/pinyin
 * 在 fcitx 配置中选择自定义双拼
