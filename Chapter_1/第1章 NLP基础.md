# 大纲

- NLP基础概念

- NLP的发展与应用

- NLP常用术语以及扩展介绍

---

# 1.1 什么是NLP

- 基本分类

![NLP基本分类](https://i.loli.net/2019/08/26/9Lmo7Up4OQXg1Hd.png)

- 自然语言生成（Natural Language Generation,NLG）

	指从结构化数据中以读取的方式自动生成文本，主要包括三个阶段：

	- 文本规划：完成结构化数据中的基础内容规划；
	- 语句规划：从结构化数据中组合语句来表达信息流；
	- 实现：产生语法通顺的语句来表达文本；

- 研究任务

	- 机器翻译
	- 情感分析
	- 智能问答
	- 文摘生成
	- 文本分类
	- 舆论分析
	- 知识图谱

---

# 1.2 NLP的发展历程

- 萌芽期（1956年以前）

	贝叶斯方法、隐马尔可夫、最大熵、支持向量机……，主流仍为基于规则的理性主义方法；

- 快速发展期（1980~1999年）

	基于统计、基于实例和基于规则的语料库技术在这一时期蓬勃发展；

- 突飞猛进期（2000年至今）

	神经网络与深度学习；

---

# 1.3 NLP相关知识的构成

- 基本术语

	- 分词（segment）
	- 词性标注（part-of-speech tagging）
	- 命名实体识别（NER，Named Entity Recognition）

		指从文本中识别具有特定类标的实体（常为名词），如人名、地名、机构名、专有名词等；

	- 句法分析(syntax parsing)

		目的是解析句子中各个成分的依赖关系；

	- 指代消解（anaphora resolution）
	- 情感识别（emotion recognition）
	- 纠错（correction）
	- 问答系统（QA system）
- 知识结构

	NLP是一门跨学科科学，体系化与特殊化并存，其知识体系如下：

	- **句法语义分析**：针对目标句子，进行各种句法分析；
	- **关键词抽取**：抽取目标文本中的主要信息；
	- **文本挖掘**：主要包含对文本的聚类、分类、信息抽取、摘要、情感分析及对挖掘的信息和知识的可视化、交互式的呈现界面；
	- **信息检索**：对大规模的文档进行索引；
	- **机器翻译**：将输入的源语言文本通过自动化翻译转化为另一种语言的文本；
	- **问答系统**：针对某个自然语言表达的问题，由问答系统给出一个精确答案；
	- **对话系统**：系统通过多回合对话，与用户进行聊天、问答、完成某项任务；

![知识结构图示](https://i.loli.net/2019/08/26/LBWhK5q8V4Zd6JF.png)

---

# 1.4 语料库

- [中文维基百科](https://dumps.wikimedia.org/zhwiki)

- [搜狗新闻语料库](https://download.labs.sogou.com/resource/ca.php)

- [IMDB情感分析语料库](https://www.kaggle.com/tmdb/tmdb-movie-metadata)

- [fastText词向量](https://fasttext.cc/docs/en/pretrained-vectors.html)

- [维基可比语料](https://linguatools.org/tools/corpora/wikipedia-comparable-corpora/)

---

# 1.5 探究NLP的几个层面

- 第一层面：词法分析

	- 分词

	- 词性标注

		目的是为每个词赋予一个类别；

- 第二层面：句法分析

	对输入的文本以句子为单位，进行分析从而得到句子的句法结构的处理过程；

- 第三层面：语义分析

	语义角色标注（semantic role labeling）是成熟的浅层语义分析技术；