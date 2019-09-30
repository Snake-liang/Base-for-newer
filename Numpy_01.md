初学Python 数据分析
Numpy的学习使用
In [3]:

1
import numpy as np
2
​
3
a = np.array([1,2,5])
4
b = np.array([[1,2,5],[216,6516,54165]])
5
print(a)
6
print(b)
7
c = np.arange(20).reshape(4,5)
8
print(c)
9
​
10
d = np.genfromtxt("NBA.txt", delimiter = ",", dtype = str)
11
print(d)
12
​
[1 2 5]
[[    1     2     5]
 [  216  6516 54165]]
[[ 0  1  2  3  4]
 [ 5  6  7  8  9]
 [10 11 12 13 14]
 [15 16 17 18 19]]
['Player      Nominal Points   Assists   Rebounds'
 'Harden          29.8          8.8         5.6'
 'James           19.8          2.8         5.3'
 'Kevin           39.8          6.8         10.3']
