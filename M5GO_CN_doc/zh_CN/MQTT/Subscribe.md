# Subscribe订阅
__________________________

#### 功能说明

>Subscribe订阅指的是，通讯中接收数据的环节，当发布者发布了信息后，订阅者将自动接收已订阅的主题（topic），消息内容（msg）

* __Subscribe “主题”（topic）__

>![Subscribe1](/image/MQTT/Subscribe1.jpg)

>设定要订阅的主题

* __Get topic data “内容”（msg）__

>![Subscribe2](/image/MQTT/Subscribe2.jpg)

>获取该订阅下的消息内容

#### 使用方法

>添加Subscribe块，并填写要订阅的主题（topic），使用Get topic data块获取，并处理分析，例：

>当从Publish那获取了一个"open"，点亮RGB bar，当获取到"close"，则熄灭RGB bar

>![Subscribe3](/image/MQTT/Subscribe3.jpg)

