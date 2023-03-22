# Intramural-competition
# 校内赛
##比赛小车
芯片选用STM32F103C8T6
1. 小车具备循迹，遥控功能。实际比赛分为三个步骤，循迹，定点，以及遥控夹取物料。
2. 循迹部分采用三路循迹，只有三个对管（没多上是因为当时快递不通，物资短缺），感觉对管越多越容易提速，但提速无法避免的是可能会冲出赛道。
3. 定点部分，由于是紧随循迹部分之后，在两个赛道交界处有一个挡板，可以被小黄管检测到，所以由小黄管来进行识别是否进入定点区。
4. 定点也是采用对管检测黑线，由于赛道是由多个黑色边框，中心黄色正方形组成的，所以对管检测计数效果还可以。
5. 最后就是夹取物料放到台子上，这个无需多言。
##遥控器选用STM32F103
1. 遥控器主要是靠蓝牙和小车通信，同时配置了摇杆（效果不是非常好，可能和摇杆老旧有关）
