# goyoe-hosts
说在前面

hosts不能上YouTube看视频！！！
hosts不能上YouTube看视频！！！
hosts不能上YouTube看视频！！！

重要的事情讲三遍

使用方法

Widonws系统：

 到C:\windows\system32\drivers\etc下查找hosts文件并以记事本打开，然后复制以下谷歌-Hosts代码进去，最后保存。（记得hosts文件是无后缀的哦！）
 
Linux系统

 请修改 /etc/hosts 这个文件
安卓同上，但要ROOT

高大上的MAC系统

 如果是苹果电脑（Mac ）请打开你的文件管理器（也就是Finder）
 然后，请按快捷键组合“Shift+Command+G”三个组合按键查找文件，并输入Hosts文件的所在路径：/etc/hosts。
 其次，在打开的文件夹中找到“Hosts”文件夹。
更改后请做如下操作

 Windows
 
 开始 -> 运行 -> 输入cmd -> 在CMD窗口输入
 ipconfig /flushdns
 
Linux

 终端输入
 sudo rcnscd restart
 对于systemd发行版，请使用命令
 sudo systemctl restart NetworkManager
 如果不懂请都尝试下
 
Mac OS X

终端输入
 sudo killall -HUP mDNSResponder
 
 Android
 
 开启飞行模式 -> 关闭飞行模式
 
通用方法

 拔网线(断网) -> 插网线(重新连接网络)
 

下载前的声明:

1.近期各地对谷歌的封锁程度越来越重，我们谷友部落格没有能力对抗国家的封锁，因此，我们的Hosts 不保证7*24小时可用，也不保证全国各地各运营商都适用，但欢迎大家给我们反映无法访问的地区，我们也将尽力提供全能的Hosts。

2.由于当局对Youtube的封锁远比Google厉害，我们提供的Hosts只能访问Youtube网页，暂不能观看视频，需要观看视频的请自行下载Lantern或者使用VPN。

3.为了使我们的Hosts更加稳定，请访问时尽量使用https访问，如https://google.com.hk，使用http访问不但容易使你无法访问谷歌，并且容易使我们的IP被封。

最后，我衷心希望大家明白：IP不易，FQ不易。
