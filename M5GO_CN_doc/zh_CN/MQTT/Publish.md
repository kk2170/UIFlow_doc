# Publish发布
__________________________

#### 功能说明

>Publish发布指的是，通讯中发布数据的环节，为发布内容包含两个部分 “主题”（topic），“内容”（msg）

>![Publish](/image/MQTT/Publish.jpg)

>* __Publish “主题”（topic）__
设定一个发布主题，当其他设备想要获取该主题下的内容信息时，则需要订阅相匹配的主题名

>* __Publish “内容”（msg）__
设定要发布的内容信息

#### 使用方法

>当程序运行到Publish发布块时，进行消息发布。例：当按下A按钮时，进行消息发布
<!-- >![Repeat_user](/image/Loops/Repeat_user.gif) -->

