# SLAM基础问题

#### 1.欧式变换，相似变换，仿射变换，射影变换的区别？
**欧式变换**
首先**欧式变换**是将刚体在三维环境中原封不动的进行旋转或者平移。

**相似变换**
$$
Ts = \begin{bmatrix}
sR  & t \\
0^{T} & 1
\end{bmatrix}
$$

2.Homograph 和 Fundamental Matrix 的区别，有几个自由度，为什么有这么多自由度，如何计算？

3.Essential Matrix的推到与计算？