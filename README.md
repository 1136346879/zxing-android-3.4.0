# android
Zxin--二维码扫码
最近 应用中需要集成扫码功能，然后调研了一下，zxing这个第三方库，demo已经可运行，扫码还是挺灵敏的。可以满足基本App的需求。
源码在最下方，可以直接去github下载。

识别二维码过程：
扫码效果大家可以看看：
![image](image https://img-blog.csdnimg.cn/20200811190559935.gif)

应用设置页面

![image](image https://img-blog.csdnimg.cn/20200811185418171.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dkeF8xMTM2MzQ2ODc5,size_16,color_FFFFFF,t_70)

示例二维码：
![image](image https://img-blog.csdnimg.cn/20200811185407362.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dkeF8xMTM2MzQ2ODc5,size_16,color_FFFFFF,t_70)

zxing3.4.0-android-github源码地址（demo）

对了 还有一个注意点：
zxingdemo运行，必须安装 google play 应用商店，所以 在华为手机上市不能使用的。

我在使用过程中 ，发现问题所在：
但是在精度，图片识别速度，灵敏度，对小的二维码，强光照、污损、柱面等影响下就很难识别出来。
正在寻求解决方法，大家如果有好的方法，可以在评论区发出来，大家一块讨论学习。
QQ： 1136346879
有问题，可以加QQ一块讨论。
