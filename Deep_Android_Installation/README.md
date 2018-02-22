This version is specially adapted to Android system,and because of rush time,I did not make a zip file to be used in TWRP recovery mode.You can install it by refering folowing information.

这个版本的是深度嵌入安卓系统，因为时间问题，没有做一个TWRP下直接刷入的zip文件，你可以参考下面的信息自己安装。


Attention:get root access before runing command and your device must had been unlocked bootloader.Here is the problem,I did not check wether those command would work,so please check those command carefully before excute them,I did not mean to break your device!


注意:执行前必须获取root权限以及解锁系统分区，我并没有测试如下命令，请仔细检查是否有错误，如果损毁你的设备跟我没有一点关系。


```shell
if [[ $EXTERNAL_STORAGE == '' ]];then
   echo 'storage path not found.'
   exit 1
fi
cd $EXTERNAL_STORAGE
mkdir Temp
cd Temp
if [[ `which curl` == '' ]];then
   echo 'curl not found.'
   exit 1
fi
if [[  `which busybox` == '' ]];then
   echo 'busybox not found.'
   exit 1
fi
curl -k -o ./Fast_Download.zip 'https://raw.githubusercontent.com/Saint-Theana/AriaNg-For-Android/master/Deep_Android_Installation/Fast_Download.zip'
busybox unzip Fast_Download.zip
busybox mount -o remount,rw /system
cp -r ./system /
chmod -R 644 /system/etc/www
chmod 644 /system/etc/aria2.conf
chmod 644 /system/etc/ariang-language.conf
chmod 644 /system/etc/ca-certificates.crt
chmod 644 /system/etc/lighttpd.conf
chmod 644 /system/lib64/libcrypto.so.1.1
chmod 644 /system/lib64/libsqlite3.so
chmod 644 /system/lib64/libssh2.so
chmod 644 /system/lib64/libssl.so.1.1
chmod 755 /system/xbin/aria2c
chmod 755 /system/xbin/ariang
chmod 755 /system/xbin/lighttpd

echo 'complete!'

sleep 2

ariang

```


手动安装方法:(Manual Installation)
1: 下载Aria2.zip  链接:https://raw.githubusercontent.com/Saint-Theana/AriaNg-For-Android/master/Deep_Android_Installation/Fast_Download.zip

2:解压后把system文件夹移动到根目录下面。

3:修改权限/system/etc和/system/lib64下的那些都是644，/system/xbin下的那些都是755






