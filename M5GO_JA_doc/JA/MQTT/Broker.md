# MQTTサーバ
_________________________________

* __MQTTサービスの選択__

>MQTTを用いたデータのやりとりにはMQTTサーバ(ブローカー:Brokerと呼ぶ)が必要です。ここではサードパーティのMQTTサーバプラッットフォームの一つであるCloudMQTTを使用して説明を行います。

>MQTTプラットフォームサービスにサーバアドレス、アカウント名、パスワードなどの設定情報をメモします。これらの情報はUIFlowのMQTTブロック内で使用します。

>![info](/image/MQTT/info.jpg)



* __MQTTの機能__

>UIFlowの高級ブロックの中にMQTT機能ブロックがあります。MQTTプロトコルは"出版"(Publish)と"購読"(Subscribe)の二つのパートにわけて理解することができます。

>Publisherがメッセージを送信し、それをSubscriberが受信して通信を行います。

><img src="/image/MQTT/UIFlow_MQTT1.jpg" width="365" />  <img src="/image/MQTT/UIFlow_MQTT2.jpg" width="365"/>
