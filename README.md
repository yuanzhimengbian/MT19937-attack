# MT19937-attack

库中主要会记录如何模拟MT19937和简单的如何使用本库

extract_Matrix.txt 一个![](http://latex.codecogs.com/svg.latex?19968 \times 19968)的矩阵，初始状态的向量右乘这个矩阵可以得到寄存器为输入状态下，伪随机数的输出值。

twist_Matrix.txt 也是一个![](http://latex.codecogs.com/svg.latex?19968 \times 19968)的矩阵，初始状态的向量右乘这个矩阵可以得到下个轮次寄存器的输出值。

![](http://latex.codecogs.com/svg.latex?19968 \times 19968)

