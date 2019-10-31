只能在Neoterm上使用!!(This Edition Can Only Be Used On Neoterm!!)

下载Neoterm: https://www.coolapk.com/apk/io.neoterm(Download Neoterm: https://www.coolapk.com/apk/io.neoterm)


使用以下命令来下载安装:(Use folowing command to download and install it:)

```shell
apt install sqlite libexpat openssl lighttpd libssh2 c-ares wget -y && wget 'https://github.com/Saint-Theana/Terminal-AriaNg-For-Android/raw/master/For-Neoterm/ariang_neoterm.deb' && dpkg -i aria2-ariang-controler_1.*_aarch64.deb
ariang
```

使用adb开启aria2c(run aria2c as user shell):
1,先打开neoterm执行以下命令(open neoterm and run following command)
```shell
chmod 755 /data/data/io.neoterm
chmod 755 /data/data/io.neoterm/files
chmod 755 /data/data/io.neoterm/files/usr
chmod 755 /data/data/io.neoterm/files/usr/bin
chmod 755 /data/data/io.neoterm/files/usr/bin/ariang
chmod 755 /data/data/io.neoterm/files/usr/bin/busybox
chmod 755 /data/data/io.neoterm/files/usr/bin/applets
chmod 755 /data/data/io.neoterm/files/usr/etc
chmod -R 755 /data/data/io.neoterm/files/usr/etc/Aria2
chmod 755 /data/data/io.neoterm/files/usr/bin/sh
chmod 755 /data/data/io.neoterm/files/usr/lib/libandroid-support.so
chmod 755 /data/data/io.neoterm/files/usr/lib
chmod 755 /data/data/io.neoterm/files/usr/lib/"libreadline.so.7"
chmod 755 /data/data/io.neoterm/files/usr/lib/"libhistory.so.7"
chmod 755 /data/data/io.neoterm/files/usr/lib/"libncursesw.so.6"
chmod 755 /data/data/io.neoterm/files/usr/bin/aria2c
chmod 755 /data/data/io.neoterm/files/usr/bin/lighttpd
chmod 755 /data/data/io.neoterm/files/usr/lib/"libssl.so.1.0.0"
chmod 755 /data/data/io.neoterm/files/usr/lib/"libandroid-glob.so"
chmod 755 /data/data/io.neoterm/files/usr/lib/"libcrypto.so.1.0.0"
chmod 755 /data/data/io.neoterm/files/usr/lib/"libpcre.so"
chmod 755 /data/data/io.neoterm/files/usr/lib/"libssh2.so"
chmod 755 /data/data/io.neoterm/files/usr/lib/mod_indexfile.so
chmod 755 /data/data/io.neoterm/files/usr/lib/"libsqlite3.so"
chmod 755 /data/data/io.neoterm/files/usr/lib/mod_dirlisting.so
chmod 755 /data/data/io.neoterm/files/usr/lib/"libcares.so"
chmod 755 /data/data/io.neoterm/files/usr/lib/mod_staticfile.so
chmod -R 755 /data/data/io.neoterm/files/usr/etc/tls/
```

2,手机上打开网络adb连接adb，或者用电脑通过usb连接adb(open network adb in your phone and use following command to connect it,or use a computer instead)
```shell
apt install android-platform-tools
adb shell
```

3,运行ariang (run ariang)
```shell
LD_LIBRARY_PATH=/data/data/io.neoterm/files/usr/lib /data/data/io.neoterm/files/usr/bin/ariang
```

 



 
