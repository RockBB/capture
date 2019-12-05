ocr截图识别

```
https://s7so.com/article/33.html
https://blog.csdn.net/mbh12333/article/details/99949059
http://www.voidcn.com/article/p-ryjlqyex-vc.html
https://ai.baidu.com/forum/topic/show/867951

https://cloud.baidu.com/
https://api.fanyi.baidu.com/api/trans/product/prodinfo
https://zhuanlan.zhihu.com/p/45288707
https://cloud.baidu.com/product/ocr/general
```



python截图+百度ocr（图片识别）+ 百度翻译

一直想用python做一个截图并自动翻译的工具，恰好最近有时间就在网上找了资料，根据资料以及自己的理解做了一个简单的截图翻译工具。整理一下并把代码放在github给大家参考。界面用python自带的GUI的tkinter，截图用的是pillow，图片识别用的是百度ocr的api，翻译用的是百度翻译api。

前期准备

python环境 

```
window 10
python3.6

baidu-aip==2.2.18.0
certifi==2019.11.28
chardet==3.0.4
idna==2.8
Pillow==6.2.1
requests==2.22.0
urllib3==1.25.7
```



安装第三方包

```
pip install pillow
pip install baidu-aip
```



百度ocr的api申请步骤参考

```
https://ai.baidu.com/forum/topic/show/867951
```



百度翻译api申请步骤参考

```
https://www.91yun.co/archives/66
```



tkinter教程参考

```
https://morvanzhou.github.io/tutorials/python-basic/tkinter/2-07-canvas/
```



pillow教程参考

```
https://www.cnblogs.com/wbin91/p/3971079.html
```

