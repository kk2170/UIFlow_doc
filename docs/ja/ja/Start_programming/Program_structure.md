# プログラムの構造
____________________________________

#### Setupブロック

>UIFlowを開くと、最初にSetupブロックがあるのがわかります。プログラムは必ず、Setupブロックから開始され、1度だけ実行されます。

>![Setup](/image/Program_structure/Setup.png)


#### Loopブロック

>Loopは無限ループブロックです。実行されると、何らかのイベントが発生して停止するまで、ブロックに含まれるプログラムが無限に繰り返し実行されます。

>![Block_connect](/image/Program_structure/Loop.png)


#### プログラムの接続

>ジグソーパズルのように、ブロック間の凸凹を使用して異なるブロック同士を接続することができます。

>![Block_connect](/image/Program_structure/Block_connect.gif)

#### プログラムの実行順序

>プログラムは上から下に向かって実行されます。プログラムが開始されるとSetupブロックが一度だけ実行され、その後Loopがブロックが繰り返し実行されます。

><img src="/image/Program_structure/Process.png"/>