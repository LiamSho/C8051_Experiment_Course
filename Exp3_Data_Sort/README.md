# 实验3 数据排序

## 一、实验目的
1. 熟悉51单片机体系结构，掌握程序设计方法。
2. 掌握排序程序的设计方法。

## 二、实验内容
1. 本例程采用交换排序法将内部RAM 中的30～39H 单元中的10个单字节无符号二进制数
按从小到大的次序排列；
2. 将排序后的数据中的最大的一个数和最小一个数去掉,求其他八个数的和,和放40H,41H
中, 求这八个数的平均值,放在50H中。
3. 数据排序可采用：冒泡法、插入法等C语言8大经典排序算法。

## 三、实验步骤
1. 用 C 语言编写程序。
2. 编译、生成项目、下载程序，调试运行程序。
3. 用单步、断点、连续执行程序的方法调试程序。
4. 打开RAM数据窗口，分别观察看30H—39H、40H, 41H(02H)(0C0H)和50H(58H)的单元。