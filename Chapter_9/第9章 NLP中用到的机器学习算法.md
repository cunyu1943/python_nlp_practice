# 大纲

- 机器学习的一些基本概念：有/无监督学习、半监督学习、回归、降维等
- 机器学习常用分类算法：朴素贝叶斯、支持向量机、逻辑回归等
- 机器学习的聚类方法：k-means算法
- 机器学习的应用

---

# 9.1 简介

- 机器学习训练的要素

	- 数据
	- 转换数据的模型
	- 衡量模型好坏的损失函数
	- 调整模型权重以最小化损失函数的算法

- 机器学习中最重要的四类问题（按学习结果）

	- 预测（Prediction）：用回归（Regression，Arima）等模型；
	- 聚类（Clustering）：如K-means方法；
	- 分类（Classification）：支持向量机（Support Vector Machine，SVM）、逻辑回归（Logistic Regression）；
	- 降维（Dimensional reduction）：主成分分析法（Principal Component Analysis，即纯矩阵运算）；

- 按学习方法分
	
	- 监督学习（Supervised Learning）：给定输入$x$，如何通过在标注输入和输出的数据上训练模型而预测输出$y$；
	- 无监督学习（Un-supervised Learning）
	- 半监督学习（Semi-supervised Learning）
	- 增强学习（Reinforced Learning）