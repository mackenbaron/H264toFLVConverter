# H264toFLVConverter
a converter for H.264 file to FLV file

It seems that FFMPEG has a bug for H.264 to FLV.
So I write a converter 
----------------------------------------


Usage:
	aac -> flv ： converter 2 ffplay.aac cnvta.flv 
	h.264 -> flv : converter 1 test.264 test.flv


----------------------------------------


v 0.03 		2016.06.28
1. 把 converter 做成 lib 了

v 0.02b 	2016.06.27
1. 调整了 close 接口


v 0.02a 	2016.06.27
1. 时间戳的问题解决了


v 0.02 		2016.06.27
1. 现在支持 aac 的转换了，不过时间戳依然有问题，打算下个补丁搞定


v 0.01a 	2016.06.24
1. 修改了命令行输入方式，为支持 aac 文件做准备


v 0.01 		2015.11.23
1. 初始版本
2. 完成基本的264文件转flv格式文件，时间戳方面可能有问题，先将就用
