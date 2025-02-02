# -
基于正点原子STM32F103的简易函数发生器（This is a Function Generator based on stm32）

该项目基于正点原子的基础工程，使用DMA+TIM+DAC的方式，输出正弦波、方波和三角波。
输出频为1Hz——30KHz，输出高频率PWM波时会有失真，这是由于正点原子板子上的DAC引脚并没有定时器输出复用，所以只能用DAC的方式输出PWM，该方式的装换率较慢。

本项目用户的全部代码都在main.c函数中，里面有详细的注释，用户可自行阅读和修改。

![b5c0f9a87809aecca505d46e3b39351](https://github.com/user-attachments/assets/3a640abb-e07c-4b9b-bfb1-f689ea57d2d7)
