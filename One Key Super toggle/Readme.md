这是一对脚本绑定，可以通过一个按键切换超级模式的开启和关闭，前提是您已经使用正确的权限进行了Rcon身份验证。
当超级模式激活时，游戏内的生命值和弹药显示将被隐藏，以便更容易区分两种模式。我在这里将默认绑定设置为"i"键。
使用以下命令进行初始化：`exec SuperOff.cfg`

关于+toggle的注意事项：在配置文件/脚本中，+toggle相当于设置一个值，因此
`+toggle cl_showhud_healthammo 1 0`
`cl_showhud_healthammo 0`
在配置文件/脚本中是一样的，因为：
1. 没有按键按下的时间，它会立即执行并将命令设置为给定的值。
2. +toggle不会检查当前值，它只会通过按键状态改变值[VIA](https://www.merriam-webster.com/dictionary/via)，这意味着`cl_showhud_healthammo`的当前值是无意义的。




A pair of Script-Binds that Toggles Super on & off with one key, providing you have already authenticated Rcon with the right privileges.
the ingame HUD element for Health + Ammo is hidden when Super is active for easy differentiating between the two modes. I use "i" here as the default bind.
Initiate with: `exec SuperOff.cfg`


Note About +toggle: in Config's/Script's +toggle is the equivalent to setting a value, so   
`+toggle cl_showhud_healthammo 1 0`   
`cl_showhud_healthammo 0`   
are one & the same(in the case of Config's/Script's) as
1. there is no Key Held down time, it's executed instantly & just sets the command to the given value.
2. +toggle does not check the current value, it simply changes the values [VIA](https://www.merriam-webster.com/dictionary/via) the key press state, meaning the current value of `cl_showhud_healthammo` is meaningless.






  
