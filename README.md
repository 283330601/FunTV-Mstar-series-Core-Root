风行电视Mstar系列精简&root教程
===========================
FunTV-Mstar-series-Core-Root
===========================

理论上也支持其他所有Mstar系列芯片的安卓智能电视
---------------------------
如果觉得教程不错希望你能支持一下
---------------------------

![](https://wx1.sinaimg.cn/mw690/964878e4gy1gfn7olgbarj20go08ctb9.jpg)  


精简固件教程开始
---------------------------

1.从百度云网盘按实际机型下载官方固件
---------------------------

  下载地址：
  
    638：
    
    链接：https://pan.baidu.com/s/1OvSkfgozeHSmOn9XcEZPXA
    提取码：tciq
    
    938：
    
    链接：https://pan.baidu.com/s/1QlZG_RhuR4nJC9GpARiuQg
    提取码：hymi
    
    648：
    
    链接：https://pan.baidu.com/s/1dIUpZwW5XvdPnLfpEIIWAA
    提取码：9ady
    
    338：
    
    链接：https://pan.baidu.com/s/1FklQ6dS1XPa6zSvYiqnJbg
    提取码：gpn7

2.下载该项目所有源码并解压到桌面
---------------------------

3.下载一个好用的HEX编辑器，我用的是 HxD Hex Editor
---------------------------

4.用HxD Hex Editor打开固件文件（BIN）
---------------------------

5.拉到最下面，记录下最后几位，比如下图中我打开的是938系列芯片的固件，这个数字是
---------------------------
    12346938


![](https://wx2.sinaimg.cn/mw690/964878e4gy1gfn7og7cvij20ul0kldid.jpg)  

6.安装python，最好是安装最新版
---------------------------
（https://www.python.org/downloads/windows/ ）

7.WIN+R打开cmd命令提示符，输入
---------------------------
    CD XX
 (XX指代你存放下载的源码的目录)，例如：
    CD C:\Users\Lemon\Desktop\FunTV-Mstar-series-Core-Root

8.解包，输入
---------------------------
    unpack.py Mstarupgrade.bin
（其实也可以直接把unpack.py拖进去，空格，再把固件文件拖进去）

9.解包完成后会得到unpacked文件夹，打开，会看到system.img
---------------------------

10.使用ROM精灵等软件编辑或精简固件
---------------------------
（具体教程百度很多，顺带加入ROOT的教程也有，这里我就不啰嗦了）

11.编辑config.ini
---------------------------
打开FunTV-Mstar-series-Core-Root\configs\D58Y-system-tvconfig.ini这个文件，
将
    MAGIC_FOOTER=12346648
这一行的12346648改为你用HEX编辑器看到的那几个数字，
保存更改。并把unpacked文件夹改名为pack

12.打包做好的精简固件
---------------------------
回到CMD命令行窗口，输入
    pack.py C:\Users\Lemon\Desktop\FunTV-Mstar-series-Core-Root\configs\D58Y-system-tvconfig.ini
（ini文件位置自己注意更换,或者直接把pack.py拖进去，空格，再把ini文件拖进去）

13.得到一个BIN格式的固件包，可以准备刷机了。
---------------------------

14.刷原厂包
---------------------------
先把百度云下载的原厂固件更名为“Mstarupgrade.bin”，放入U盘，电视关机并拔掉电源线。插入u盘并按住电源键，插入电源线，等到蓝色刷机界面松开电源键等待刷机进度条走完。

15.刷完官方固件开机，不要联网，先连接遥控器，所有设置按自己习惯设置好，关机。
---------------------------

16.把自己动手做好的固件包放在U盘里，也重命名为Mstarupgrade.bin。
---------------------------

17.电视关机并拔掉电源线。插入u盘并按住电源键，插入电源线，等到蓝色刷机界面松开电源键等待刷机进度条走完。
---------------------------

18.Done!
---------------------------

如果觉得教程不错希望你能支持一下
---------------------------

![](https://wx1.sinaimg.cn/mw690/964878e4gy1gfn7olgbarj20go08ctb9.jpg)  



刷好后的界面如下所示：
---------------------------
首先是我自定义的启动画面

![](https://wx2.sinaimg.cn/mw690/964878e4gy1gfn7noig5lj20iw0e6abl.jpg)  

启动画面过后直接进入沙发桌面了，启动过程大概15秒。

![](https://wx1.sinaimg.cn/mw690/964878e4gy1gfn7nr0oijj20iw0e6why.jpg)  

root授权管理软件没有选择SUPERSU是因为SU用遥控器不蛮好操控

![](https://wx1.sinaimg.cn/mw690/964878e4gy1gfn7ntdnvcj20iw0e6dhp.jpg)  

授权管理页

![](https://wx3.sinaimg.cn/mw690/964878e4gy1gfn7nvfdicj20iw0e60to.jpg)  

设备信息页

![](https://wx3.sinaimg.cn/mw690/964878e4gy1gfn7nxgwq8j20iw0e6406.jpg)  

信号源切换也很流畅

![](https://wx1.sinaimg.cn/mw690/964878e4gy1gfn7od22plj20iw0e6jtj.jpg)  

如果觉得教程不错希望你能支持一下

![](https://wx1.sinaimg.cn/mw690/964878e4gy1gfn7olgbarj20go08ctb9.jpg)  
