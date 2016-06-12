# WinMTR 显 ip 所在地版

## 用法

下载，编译，放入纯真ip库，运行。

## 瞩目

1. 本项目已经有编译好的版本，参见 [Releases](https://github.com/oott123/WinMTR/releases) 页面。
2. 要想自己编译的，可以参考 [这条V2EX上的相关讨论](https://www.v2ex.com/t/176537#reply10) 的 6#。

v12是指VS 2013，你是2012（即v11），所以提示缺失工具集
		          Reply    6
stupidcat   2015-03-13 10:28:35 +08:00   ♥ 1
VS 2013提示缺少nafxcw.lib，搜了下说“Multibyte MFC Library was deprecated in VS2013”，所以还需要下载这个： http://www.microsoft.com/en-us/download/confirmation.aspx?id=40770
		          Reply    7
bestsanmao   2015-03-13 10:37:26 +08:00   ♥ 5
编译好了 
https://www.dropbox.com/s/mb8hnhv4zvkz19q/WinMTR.zip?dl=0 

含最新纯真IP库
		          Reply    8
scys   2015-03-13 10:50:04 +08:00
@bestsanmao 感谢~ 
@sky92682 顺道拿了个：P
		          Reply    9
sky92682   2015-03-13 11:15:29 +08:00
十分感谢楼上各位热心朋友的帮助 感激不尽
		          Reply    10
oott123   2015-03-13 14:52:52 +08:00
简直了！你们都没看到我发了 release 么？ 
https://github.com/oott123/WinMTR/releases 
@stupidcat 确实是需要那么个玩意儿233
		          Reply    11
coldswell   2015-04-01 15:22:17 +08:00
有linux版本的吗？
		          Reply    12
ve2x   2015-05-23 16:19:15 +08:00
@oott123 
@bestsanmao 

可以编译成不限ping次数吗 7次就自动停止太短了
		          Reply    13
oott123   2015-05-23 16:41:28 +08:00
@ve2x 去掉这一行就可以了 
https://github.com/oott123/WinMTR/blob/master/WinMTRDialog.cpp#L1225 
编译请自己动手。
		          Reply    14
ve2x   2015-05-23 20:22:54 +08:00
@oott123 好吧 .. 从来没有弄过 不知道从哪里下手...
		          Reply    15
oott123   2015-05-23 22:20:15 +08:00 via Android
@ve2x 安装 vs 2013 和 6楼给的链接，下载代码，双击 sln 文件，点编译。 
我机器重装了，没 vs
