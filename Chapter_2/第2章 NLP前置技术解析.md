# 大纲

- 选择Python作为自然语言开发语言的理由

- 安装与使用Anaconda

- 正则表达式

- Numpy

---

# 2.1 搭建Python开发环境


- Python优势：

1. 丰富的自然语言处理库；
2. 编程语法简单易理解；
3. 许多数据科学相关的库；

- Anaconda

	安装以及简单实用教程见[Anaconda简单实用手册](https://blog.csdn.net/github_39655029/article/details/85238899)或[廖雪峰的Python教程之正则表达式教程](https://www.liaoxuefeng.com/wiki/1016959663602400/1017639890281664)；

---

# 2.2 正则表达式在NLP中的基本应用

书中知识较为简单，想要深入学习请参考相关教程[菜鸟教程之正则表达式](https://www.runoob.com/regexp/regexp-syntax.html)

---

# 2.3 Numpy使用详解

- 主要功能

	- ndarray，一个具有向量算数运算和复杂广播能力的多维数组对象；
	- 用于对数组数据进行快速运算的标准数学函数；
	- 用于读写磁盘数据的工具以及用于操作内存映射文件的工具；
	- 线性函数、傅里叶变换和随机数操作；
	- 用于集成C/C++和Fortran代码的工具；

- 相关教程

	- [Numpy参考手册](https://www.numpy.org.cn/reference/index.html)
	- [CS231n课程笔记翻译：Python Numpy教程](https://zhuanlan.zhihu.com/p/20878530)

- 简单使用

```python

#--*--coding:utf-8--*--

import numpy as np

# 直接导入向量
vector = np.array([1,2,3,4])
# 导入矩阵
matrix = np.array([[1,'Duncan'],[2,'Manu'],[3,'Paker'],[4,'Green']])
# 自动架构一个多行多列的array对象
a = np.arange(15).reshape(3,5)
# 获取Numpy中数组维度
print(a.shape)
# 获取本地数据
file = np.genfromtxt('./data/demo.txt',delimiter=',')
print(file)
# 正确读取数据
file_new = np.genfromtxt('./data/demo.txt',dtype = 'U75',skip_header=1,delimiter=',')
print(new_file)
# 索引
matrix_new = np.array([[1, 2, 3],[40, 50, 60]])
print(matrix[1, 2])
# 数组比较
m = (matrix_new == 10)
print(m)
```



