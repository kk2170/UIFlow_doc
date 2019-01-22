# Subscribe(購読)
__________________________

#### 機能説明

>Subscribe(購読)は、MQTT通信でデータを受信するために使用します。出版者(Publisher)がメッセージを送信すると、購読者(subscriber)は登録されているトピックのメッセージの内容を受信します。

* __Subscribe “トピック”（topic）__

>![Subscribe1](/image/MQTT/Subscribe1.jpg)

>購読するトピックを設定してください。

* __Get topic data “内容”（msg）__

>![Subscribe2](/image/MQTT/Subscribe2.jpg)

>購読しているトピックのメッセージの内容を取得します。

#### 使用方法

>「Subscribeブロック」を追加し、購読するトピック（topic）を設定します。「Get topic dataブロック」でメッセージを分析・取得します。例：

>Publishから"open"が取得されると、RGB barを点灯し、"close"を取得するとRGB barを消灯します。

>![Subscribe3](/image/MQTT/Subscribe3.jpg)

