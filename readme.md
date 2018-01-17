# 斯特沃克作业-无人机信息输出
<p align="right">----by 黄荣</p>
<p align="right">2018-1-17</p>
----
##文件编译环境及运行
###1.基于ubuntu中的gcc编译
此文件编译基于ubuntu中gcc编译器编译，在命令行中直接输入：
```cmd
gcc TW_Homework_Hilree.c
```
得到a.out文件，命令行运行格式如下：
```cmd
./a.out xxx.txt ID
```
此后会打印在console上，显示相对应的输出。
![ubuntu中编译][1]
###2.基于win中的IDE编译
若在win中的IDE编译，则需要在代码的第一行加上
```cmd
#include "stdafx.h"
```
编译后得到TW_Homework_Hilree.exe文件，命令行运行格式如下：
```cmd
TW_Homework_Hilree.exe xxx.txt ID
```
----
##针对输入参数稍不正确情况
![error输入参数][2]

----
##测试样例
针对多种情况，我准备了三种样例：
###样例1:test_Alpha.txt
```test_Alpha.txt
Alphaplane 1 1 1
Alphaplane 1 1 1 1 2 3
Alphaplane 2 3 4 1 1 1
Alphaplane 3 4 5
Alphaplane 1 1 1 1 2 3
```
![样例1][3]
###样例2:test_Beta.txt
```test_Alpha.txt
Betaplane 1 1 1
Betaplane 1 1 1 2 3 4
Betaplane 3 4 5 -2 -2 -2
Betaplane 1 2 3 -20 -44 -623
Betaplane -33 -44 -55 1 1 1
Betaplane -32 -43 -54 1 1 1
```
![样例2][4]
###样例3:test_Name.txt
```test_Alpha.txt
superPlane 1 1 1
superPlane 1 1 1 2 3 4
superHero 3 4 5 -2 -2 -2
superPlane 1 2 3 -20 -44 -623
superPlane -19 -42 -620 200 200 200
superPlane 181 158 -420 1 1 1
```
![样例3][5]

----


