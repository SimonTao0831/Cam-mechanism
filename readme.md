# 凸轮机构设计程序
这是我的机械原理的大作业，利用计算机进行机械设计，
原题为高等教育出版社机械原理（第七版）的4-12。
---
## 要求
每隔5°计算并打印凸轮理论轮廓曲线与实际轮廓曲线上点的直角坐标和压力角数值。
---
## 说明
这是我用c写的程序，相较于用matlab写的程序，着实复杂不少，再不调用外界库的情况下，求导、求最大值、画图等函数均需要编写，
而matlab中这些函数均已被撰写，可以直接调用，总而言之，数学问题的编程我还是倾向于matlab的。
- start.exe执行运算。
- zuobiao.csv文件是写入的数据，会在start.exe目录下创建。
- 在ifconfig函数中，可以定义凸轮的初始变量。
- 在functions函数中，可以定义每一段s-Phi的关系。
- 这里我想使程序的修改量尽量减小，但目前在更改分段函数后仍需手动修改后续函数式。
---
本人在读大学生，程序尚不精进，过于冗余，如有疑问欢迎交流。
我的邮箱：ximengtaox@gmail.com
---