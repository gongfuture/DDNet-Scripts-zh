这是在不冻结之前将dummy HammerThrow到某个方向的绑定。

首先，你需要选择你想要将dummy扔向右边还是左边。你可以通过绑定 bind x exec activate_dummy_mover.cfg 并按下x来做到这一点。接下来按下a或d将执行onright.cfg或onleft.cfg。 如果你正在HammerFlying，释放mouse1并使用mouse2继续HammerFly，直到你想要扔掉你的dummy。 现在你可以将dummy扔向指定的方向并用锤子击打它，现在按下mouse1用于锤子会做多件事，它会立即切换到dummy，同时按住+right/+left，你会通过DeepFly被主tee的锤子击中。 这将只会工作一次，然后它将重新绑定deepfly并解绑HookDeepFly。通过按下x重复。

解释为什么这样做： +right/+left是临时绑定在mouse1上，因为在dummy切换时，a/d需要重新按下才能再次工作（这会导致tee失去动力） activate_dummy_move.cfg将dummy HammerFly绑定在mouse2上，因为有一个bug，当mouse1仍然被按下时，会导致a/d移动的延迟。如果你之前没有DeepHammerFly（例如在地面上），它将在没有这个解决方案的情况下工作 DeepFly在最后被打开，因为大多数时候之后需要它。 可以+toggle dummy，这样你可以很快返回到主tee，但请记住，用+toggle命令重新绑定一个被按住的键总是会导致bug 它们是像DeepFly延迟这样的bug，但只对一个tee有效，当切换移动的方向或使用的tee时，它就会工作。我不知道为什么。

要启动：执行 "show_others_on.cfg"，然后在游戏中使用X来切换开关。

作者：kamillentee // https://forum.ddnet.tw/memberlist.php?mode=viewprofile&u=208

注意：复制&粘贴，如果对此有任何问题和评论，请直接向作者提问。

ps:这段直接用的机翻，不大能理解



Bind to HammerThrow dummy to a certain direction without freezing it before

First you need to choose whether you want to throw the dummy to the right or to the left. You do this by binding bind x exec activate_dummy_mover.cfg and pressing x. The next pressing of either a or d will execute onright.cfg or onleft.cfg.
If you are HammerFlying release mouse1 and use mouse2 to continue with the HammerFly until you want to throw your dummy.
Now you can throw the dummy to the specified direction and hammer it , pressing mouse1 now for hammer does multiple things it immediately switches to the dummy while holding +right/+left and you get hit with the hammer of the main tee via DeepFly.
That will work exactly one time and then it will rebind deepfly and unbind HookDeepFly. Repeat by pressing x.

Explanations why its done this way:
+right/+left is temporary binded on mouse1 because on dummy switch a/d would need to be repressed to work again (which causes the tee to loose momentum)
activate_dummy_move.cfg is binding dummy HammerFly on mouse2 because there is a bug that causes a delay for a/d movement when mouse1 is still pressed. It will work without this workaround if you don't DeepHammerFly before (e.g. on ground)
DeepFly is turned on at the end because most of the time it's needed afterwards.
it is possible to +toggle the dummy so you can return very fast to the main tee, but keep in mind that rebinding a key that is held with a +toggle command always causes bugs
They are bugs like DeepFly delay but only for one tee, when switching either direction of movement or the used tee it works. I have no idea why.


To initiate: exec "show_others_on.cfg"  Then use X in-game to toggle it on & off.

 Author: kamillentee // https://forum.ddnet.tw/memberlist.php?mode=viewprofile&u=208

note: Copy&Pasted, please direct questions & comments for this to the author
