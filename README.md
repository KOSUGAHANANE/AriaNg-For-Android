# Ariang 手机端
在手机上运行的Ariang服务

分为三个版本。
1(NeoTerm_Edition):这个版本的只能用在NeoTerm上，而且可以不需要root就能运行，不过需要把NeoTerm挂在后台不然进程会被杀掉，不过你也可以用adb来开启aria2c，这样就不用把NeoTerm挂在后台了。如果手机有网络adb的话直接就更方便了，直接在本机就能开启。这个版本推荐给没有root的机器使用。(没有root应该没法访问外置储存目录，不过adb权限我没试过)

2(Android_Edition):需要用twrp卡刷，安装到/system/目录后怎么恢复出厂设置都不怕了。

3(MT_Edition):这个版本只能用在2.8.2版本以上的mt管理器上，用终端模拟器来运行。

Ariang android edition<br>
Ariang runing on android device.

This Project was parted to 3 Edition:
 
1(NeoTerm_Edition):
This edition can only be used on NeoTerm.
This Edition should be helpful to those who cannot got there device rooted.


2(Android_Edition):
This edition requires twrp recovery mode and unlock bootloader.<br>
And it will be installed inside android system.


3(MT_Edition):
This edition can only be used on MT Manager 2.8.2 or above.
This Edition should be helpful to those who cannot got there device rooted.




One attention.Running as root can promise aria2c always running in backround,and highest permission to write file in file system.If you cannot get your device rooted,it also works in unrooted environment.But here's what you should know:
When you shut TerminalEmulator app down completely,the process of aria2c dies with it.
One solution is running aria2c as user shell(2000,adb).
Not running as root may not have permission to download files to most path in Disk card,the ideally way is set download-dir to path '<DISK>/Android/data/io.neoterm/'.
<br>