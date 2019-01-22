# Publish(出版)
__________________________

#### 機能説明

>Publish(出版)は、MQTT通信で“トピック”（topic）と“内容”（msg）の二つを含むデータを送信します。

>![Publish1](/image/MQTT/Publish1.jpg)

* __Publish “トピック”（topic）__

>トピックを設定します。他のデバイスがメッセージ内容を取得したい場合には、一致するトピックを購読する必要があります。

* __Publish “内容”（msg）__

>Publisherは内容を設定します。

#### 使用方法

>Publishブロックが実行されるとメッセージが送信されます。例：
>Aボタンを押すと、次のメッセージを送信します。(トピック"RGB",内容"open")
>Bボタンを押すと、次のメッセージを送信します。(トピック"RGB",内容"close")

>![Publish2](/image/MQTT/Publish2.jpg)