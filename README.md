# Terminal-AriaNg-For-Android
一个用shell写的简单的AriaNg终端控制程序，在Neoterm或者其他的终端模拟器上运行。

I am workong on Engish translation......

have fun......

分为三个版本。
1(For_NeoTerm):这个版本的只能用在NeoTerm上，而且可以不需要root就能运行，不过需要把NeoTerm挂在后台不然进程会被杀掉，不过你也可以用adb来开启aria2c，这样就不用把NeoTerm挂在后台了。如果手机有网络adb的话直接就更方便了，直接在本机就能开启。这个版本推荐给没有root的机器使用。(没有root应该没法访问外置储存目录，不过adb权限我没试过)

2(For_Android):这个版本需要root支持，放到/data/目录，恢复出厂设置后应该会被删除。自己斟酌用哪个版本。

3(Deep_Android_Installation):这个版本显然是给有root的机器使用的，其实我完全可以弄一个卡刷包，至于为什么没弄就没有为什么了，还是手动安装吧，安装到 /system/目录后怎么恢复出厂设置都不怕了。



A simple AriaNg controler created with shell,running on Terminal emulater for Android.

I parted this Project with 3 Version:
 
1(For_NeoTerm):This Version can only be used on NeoTerm,And it can work both as root or not.But attention,When you shut NeoTerm down completely,Aria2 will be killed with NeoTerm immediately.But,you can fix it by running aria2c as user shell(2000,adb).(Not running as root may not have permission to download files to microSD card,and I have no idea if user shell can do that).(I recommend thos who can not root their device to use this version).

2(For_Android):This version requires root and will be install under /data/,that means when you wipe your phone to factory mode,you may lose thos files.

3(Deep_Android_Installation)This version requires root and unlock bootloader and will be install under /system/.
