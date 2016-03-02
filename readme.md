##Wifi Rss and Magnetic Detect

###简介
一个Android小工具，用来记录wifi信号强度，同时记录磁场等传感器测得的数据，可以为室内定位中建立指纹库。
![](https://raw.githubusercontent.com/jiangqideng/resources/master/device-2014-12-07-164903.png)

###使用说明

+ 有一些操作wifi的按钮，不用管他们。点击“开始RSS数据采集”，程序就自动打开wifi，打开传感器，开始循环地记录数据。
+ 中间有个”当前位置“，也就是说记录的数据会与这个位置标号联系在一起，可以通过”上一位置“、”下一位置“调整这个位置标号。
+ 点击”关闭RSS数据采集“，这时数据将会存入程序目录里，形成每个位置的数据存入一个txt文件。
+ 可以自己将文件导出，然后用matalb等软件进行分析处理。

###其他

现在这个程序比较简单，可以用来做做实验，以后不定期更新，看看能不能做成一个好用的指纹库生成器。
