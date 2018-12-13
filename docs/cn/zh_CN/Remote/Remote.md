# 远程控制
__________________________
#### 功能说明
>通过手机或电脑等设备进行远程控制M5GO
>![Remote](/image/Remote/Remote.jpg)
>* __Remote QRcode__
生成一个可以访问控制页面的二维码，并显示在屏幕上

>* __Remote Switch__
远程开关控制，使用前请点击Block上的齿轮按钮添加一个变量X，当控制时，闭合X传入1，断开X传入0

>* __Remote Button__
远程按钮控制，每点击一次按钮，则执行一次Block里的程序
>* __Remote Slider__
滑动条控制（使用前请点击Block上的齿轮按钮添加一个变量X，随着滑动X传入0~100的整数）

>* __Remote Label__
显示信息，可以选择一些内置提供的标签类型，或是输入自定义的文本

#### 使用方法
>添加一个二维码生成Block到程序中，添加Remote Button，放置要运行的程序到块中，运行程序
![Remote_user1](/image/Remote/Remote_user1.gif) 

#### 控制页面
>扫描M5GO屏幕上的二维码，或在UIFlow页面右上角的二维码选项下复制链接，访问控制页面

>![Remote_Phone](/image/Remote/Remote_Phone.png)