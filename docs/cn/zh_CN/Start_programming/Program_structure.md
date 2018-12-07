# 程序的结构
____________________________________
#### Setup块
>当打开UIFlow的时候，你会发现最开始就已经有一个Setup块，每个程序都必须有一个Setup块，程序是从Setup块开始运行的，并且只会运行一次，你可以把它看作一个程序的的初始化块
![Setup](/image/Program_structure/Setup.png)


#### Loop块
>Loop是一个无限循环块，当执行到它时，它会无限循环执行包含在块中的程序，直到发生一些事件使他停止，例如M5GO关机，程序中它不是必须存在的，但为了让程序持续的运行，或是实现某些功能时，你可以添加它

![Block_connect](/image/Program_structure/Loop.png)


#### 程序连接
>程序块之间可以通过块上的嵌口进行连接，就像拼图一样的操作方式
![Block_connect](/image/Program_structure/Block_connect.gif)

#### 程序执行顺序
>程序是由上往下执行，当程序开始运行，首先进入Setup单次执行初始化程序，然后进入Loop中不断循环主程序

![process](/image/Program_structure/process.png)
