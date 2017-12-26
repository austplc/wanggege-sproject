# wanggege-sproject 

##algorithm1：
★　问题描述：对于长度相同的两个字符串A和B，其距离定义为相应位置字符距离之和。两个非空格字符的距离是它们的ASCII码之差的绝对值；空格与空格的距离为0，空格与其他字符的距离为一定值k。
在一般情况下，字符串A和B的长度不一定相同。字符串A的扩展是在A中插入若干空格字符所产生的字符串。在字符串A和B的所有长度相同的扩展中，有一对距离最小的扩展，该距离称为字符串A和B的扩展距离。
对于给定的字符串A和B，试设计一个算法，计算其扩展距离。  

★　算法设计：对于给定的字符串A和B，计算其扩展距离。  

★　数据输入：由文件input.txt给出输入数据。第1行是字符串，第2行是字符串B，第3行是空格与其他字符的距离定值k。  

★　结果输出：将计算出的字符串A和B的扩展距离输出到文件output.txt  

输入字符串A:cmc  

输入字符串B：snmn  

输入固定距离k:2  

输出扩展距离：10


##algorithm2:  

★　问题描述：假设要在足够多的会场里安排一批活动，并希望使用尽可能少的会场。设计一个有效的贪心算法进行安排（这个问题实际上是著名的图着色问题。若将每一个活动作为图的一个定点，不相容活动间用边相连。使相邻顶点着有不同的颜色的最小着色数，相应于要找的最小会场数。）  

★　编程任务：对于给定的k个待安排的活动，编程计算使用最少会场的时间表。  

★　数据输入：对于文件input.txt给出的输入数据。第一行有一个正整数k,表示有k个待安排的活动。接下来的k行中，每行有2个正整数，分别表示k个待安排的活动的开始时间和结束时间。时间以0点开始的分钟计。  

★　结果输出：将编程计算出的最少会场数输出到文件output.txt.

输入文件示例　　　　　　输出文件示例  
input. txt　　　　　　　　output. txt  
5 　　　　　 　　　　　　3  
1    23  
12   28  
25   35  
27   80  
36   50

