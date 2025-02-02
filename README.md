# -
基于正点原子STM32F103的简易函数发生器（This is a Function Generator based on stm32）

该项目基于正点原子的基础工程，使用DMA+TIM+DAC的方式，输出正弦波、方波和三角波。
输出频为1Hz——30KHz，输出高频率PWM波时会有失真，这是由于正点原子板子上的DAC引脚并没有定时器输出复用，所以只能用DAC的方式输出PWM，该方式的装换率较慢。

本项目用户的全部代码都在main.c函数中，里面有详细的注释，用户可自行阅读和修改。

正弦波
![a26e01375bab1803321fdb938b8926c](https://github.com/user-attachments/assets/a6743232-28d2-451b-b865-32637ed8226d)
方波
![d9f5d7badcd6f540fa6a9e588b5e294](https://github.com/user-attachments/assets/557c341d-bfa4-4a61-aa2e-ec2a93ce6bb2)
三角波
![b02b5b77a7549420baddb4e319d5aec](https://github.com/user-attachments/assets/2fbd617f-0b9e-4606-99c5-3be318735b81)
