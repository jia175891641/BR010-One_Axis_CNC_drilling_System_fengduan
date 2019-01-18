# 简介
123
通用步进/伺服数控钻床控制器的源代，数控钻床主要用来打深孔，直径一般在14mm以下 深度在100mm以下。由数控电脑控制，能实现分段精确打孔，还有调速等功能，效率不是手工打孔可以比拟的。这里使用的控制器为[BR010可编程一体机],厂家可自主二次编程，最为关键的是全中文编程，而且带用户界面和自定义
用户菜单，而不需要像G代码控制器，用户修改一个简单的速度，必须去修改源代码，此控制器使用简单，性价比高，性能稳定，全国各地都有使用者,部分已出口，稳定性经得起考验!!
现在开源，供大家学习和参考！！
# 程序预览
![image](https://github.com/jia175891641/BR010-One_Axis_CNC_drilling_System_fengduan/blob/master/菜单配置.PNG)
![image](https://github.com/jia175891641/BR010-One_Axis_CNC_drilling_System_fengduan/blob/master/%E7%A8%8B%E5%BA%8F%E9%A2%84%E8%A7%88.PNG)
# 打孔流程
分为4段,每段深度和速度可以通过用户的中文菜单调整。
其中第3段可以设置循环打孔，循环次数可调，比如第3段深度为9mm 用户设定分3次打，那么系统会自动均分为每次打3mm ,并每次均分都有自动退出排削 
适合打长孔。
查看详细说明书
# 程序下载
      点击 右上方 绿色的`Clone or download` 再点 Download Zip 下载后解压 
      直接双击 .bent  文件，上位机会自动识别或打开，如果需要烧录进控制器，还需要购买烧录器,烧录器驱动
      温馨提示:厂家发货时候，能提供免费烧录服务，欢迎有志之仕在Github上分享您的作品
# 资料参考
如第一次接触此控制器，请先看完以下3个教程，尤其是`在线编程方法`：


##文字教程:

##视频教程：
BR010基本功能介绍：

BR010在线编程方法：

BR010脱机编程方法：  

[![Watch the video](https://github.com/jia175891641/BR010-VB-/blob/master/%E6%8D%95%E8%8E%B7.PNG)](https://cloud.video.taobao.com//play/u/140795238/p/1/e/6/t/1/50066686709.mp4)

#官方网站（建议使用电信宽带访问）  
[浙江浦江奔腾数控设备有限公司](http://www.btcnc.net/ "点击前往")  
#上位机下载  
[易语言2.0](http://www.btcnc.net/ "点击前往")  
#下载器驱动下载(CH340串口驱动)
<a href="http://write.blog.csdn.net/postlist" target="_blank">跳到自己博客列表</a>
