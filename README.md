# kuka
根据kuka机器人的D-H表编写其雅克比矩阵计算MATLAB代码
编程的思路主要为：1.编写出计算齐次变换矩阵A的函数，输入量为D-H表的四个要素。2.根据公式计算出矩阵T。3.根据得到末端执行器的位置o和姿态R。4.根据z=R·k得到zi。5.对于转动关节，计算雅克比矩阵上半部分和下半部分。6.将上半部分和下半部分的结果合在一起，构成最终的雅克比矩阵。
