# sc2_zerg_autohotkey
```


;=============虫族快捷键放这里.===开始.

;这个快捷键是把所有的基地和科技建筑都编入4.这样我们方便按4查看所有科技的升级情况.
#IFWinActive ahk_exe SC2_x64.exe


CapsLock::
MouseClick, left,,,2,0   ;最后一个参数0表示用最快速度.
Send, +{4}
return 







;注卵的.
#IFWinActive ahk_exe SC2_x64.exe


F5::


Send, {backspace}

MouseClickDrag, left,  A_ScreenWidth/2-300, A_ScreenHeight/2 -300, A_ScreenWidth/2+300,  A_ScreenHeight/2 +300 ,0

Send, {v}

MouseClick, left,  A_ScreenWidth/2  , A_ScreenHeight/2 -10,1,0  ;居中点一下
Send, 11
return 






;中的选中空闲农民设置为空格.
#IFWinActive ahk_exe SC2_x64.exe       


$Space::



Send, ^{space}



return 


```
