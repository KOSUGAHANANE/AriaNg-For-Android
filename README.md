# Terminal-AriaNg-For-Android
一个用shell写的简单的AriaNg终端控制程序，在Neoterm或者其他的终端模拟器上运行。

I am workong on Engish translation......

have fun......

分为两个版本。
1(For_NeoTerm):这个版本的只能用在NeoTerm上，而且可以不需要root就能运行，不过需要把NeoTerm挂在后台不然进程会被杀掉，不过你也可以用adb来开启aria2c，这样就不用把NeoTerm挂在后台了。如果手机有网络adb的话直接就更方便了，直接在本机就能开启。这个版本推荐给没有root的机器使用。(没有root应该没法访问外置储存目录，不过adb权限我没试过)

2(For_Android):需要twrp卡刷，安装到 /system/目录后怎么恢复出厂设置都不怕了。



A simple AriaNg controler created with shell,running on Terminal emulater for Android.

I parted this Project with 2 Version:
 
1(For_NeoTerm):This Version can only be used on NeoTerm,And it can work both as root or not.But attention,When you shut NeoTerm down completely,Aria2 will be killed with NeoTerm immediately.But,you can fix it by running aria2c as user shell(2000,adb).(Not running as root may not have permission to download files to microSD card,and I have no idea if user shell can do that).(I recommend thos who can not root their device to use this version).

2(For_Android)This version requires twrp recovery mode and unlock bootloader and will be install under /system/.
