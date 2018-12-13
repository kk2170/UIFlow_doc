# Units
__________________________
#### 什么是Unit
Unit是M5体系提供的功能拓展模块，Unit是为了实现更多复杂的功能而提供的硬件基础
![Units](/image/Units/Units.jpg)
#### 连接Unit模块
>在使用Unit功能编程前，需要将Unit连接到与其对应的端口
>![Units_cable](/image/Units/Unit.jpg) 

#### 添加Unit Block
>点击UI模拟器下方的Units选项，勾选需要添加的Unit模块，点击确定
>注：某些Unit存在初始参数设置，如Neopixel可以设置驱动的总灯数,可以单击已经添加了的Unit模块弹出属性框进行编辑
>![Units_add](/image/Units/Units_add.gif) 

#### 移除Unit Block
>点击已经添加了的Unit模块，拖动到上方的垃圾桶删除

>![Units_remove](/image/Units/Units_remove.gif) 

_________________________________
## 输入与输出
所有的Units模块都可以区分为两种类型，输入与输出

#### 输入型
>输入型的Unit主要以采集数据的形式，将外界的一些环境信息以数据的形式传输给M5GO
>我们可以通过对这些数据的运算实现控制功能
>![Units_input](/image/Units/Units_input.jpg)  

#### 输出型
>输出型的Unit主要以驱动的形式，以M5GO为控制核心，驱动外部连接的一些硬件，例如驱动舵机的旋转

>![Units_output](/image/Units/Units_output.jpg) 

## 模拟量与数字量
所有的Units模块都可以区分为两种类型，输入与输出

#### 模拟量
>模拟量是一个可持续变化的量，就像一个温度计在变化过程中会有很多个温度值
>![Units_analog](/image/Units/Units_analog.png)

#### 数字量
>数字量只存两种状态0与1，就像是一个开关一样，只有开与关两种状态

>![Units_digital](/image/Units/Units_digital.png)
