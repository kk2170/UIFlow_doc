# Program structure
____________________________________

#### Setup

>When you open UIFlow, you will find that there is already a Setup block at the beginning. Each program must have a Setup block. The program runs from the Setup block and will only run once. You can think of it as a Initialization block of the program

>![Setup](/image/Program_structure/Setup.png)


#### Loop

>Loop is an infinite loop block. When it is executed, it will execute the program contained in the block indefinitely until some event occurs to stop it. For example, M5GO shuts down, it does not have to exist in the program, but in order to let the program continue You can add it when running, or when implementing certain features.

>![Block_connect](/image/Program_structure/Loop.png)


#### Program connection

>Blocks can be connected between the blocks by means of a snap on the block, just like a jigsaw

>![Block_connect](/image/Program_structure/Block_connect.gif)

#### Program execution order

>The program is executed from top to bottom. When the program starts running, first enter the Setup single execution initialization program, and then enter the Loop to continuously cycle the main program.

><img src="/image/Program_structure/Process.png"/>