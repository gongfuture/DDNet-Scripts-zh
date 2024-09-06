# 三格水边缘跳跃

## 说明

这个脚本在需要从三格水的一个边缘跳到另一个边缘s时非常有用。按下`Ctrl+shift+d`，屏幕右侧会显示你的坐标（补充：现在在`游戏界面`-`DDRace HUD`中也可以开启）。

如果你想从坐标小数位为`0.63`、`0.66`或`0.81`的边缘跳跃到右侧，只需同时按下`Space`和`D`，这是能跳过去的。反过来从右跳左也是可以的，坐标小数位应该是`0.34`、`0.31`或`0.16`。

然而，因为`0.16`和`0.81`非常接近水，有时候可能会因为没有同时按下而跳不过去。使用[这组bind脚本](../三格水边缘跳跃{by kamillentee}/)可以防止这种情况发生。

每一边还有四个坐标，分别是`x.56`、`x.69`、`x.72`和`x.84`用于`>>>`方向，`x.41`、`x.28`、`x.25`和`x.13`用于`<<<`方向。对于这些坐标位置，你需要跳起来在地面上方一格使用使用这个脚本。

> 再提供一个记忆方法 $0.63 + 0.34 = 0.66 + 0.31 = 0.81 + 0.16 = \dots = 0.97$。

## 使用方法

使用 `bind x exec edgejump.cfg` 将其绑定到一个键。 再次按下`x`键恢复正常使用的方向键

## License

作者：kamillentee // [https://forum.ddnet.tw/memberlist.php?mode=viewprofile&u=208]

注意：仅为复制&粘贴，如果对此脚本有任何问题或评论，请直接向作者提问。

## 原README

This is usefull to jump from one edge to another through 3 freezes. If you press Ctrl+shift+d you see the your coordinates on the right side of the screen. The decimal place of it is usefull for some tricks.

If you stand on edge and want to jump to the right side with the decimal places of 0.63 or 0.66 or 0.81 you can just press jump and d at the same time and it will be a 100% jump. Reverse is possible too, there you go with the coordinates of 0.34 or 0.31 or 0.16.

Because 0.16 and 0.81 are very near to the freeze you can fail the jump sometimes. To prevent this use this config bind that presses jump and direction key at the same time.

There are 4 more coordinates per side x.56 x.69 x.72 and x.84 for >>> direction and x.41 x.28 x.25 and x.13 for <<<< direction. For those you jump and one tile above ground you use dj and direction key/bind.

Use bind x exec edgejump.cfg to bind it to a key.
Press x another time to use normal arrow keys again

 Author: kamillentee // https://forum.ddnet.tw/memberlist.php?mode=viewprofile&u=208

note: Copy&Pasted, please direct questions & comments for this to the author
