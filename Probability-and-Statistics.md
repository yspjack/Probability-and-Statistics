# 概率统计笔记

[TOC]

## <center> 1. 随机事件的概率</center>

### 1.1 随机事件与样本空间

#### **基本概念：**

- 随机试验：可重复、试验结果不止一个、不能准确预言试验结果。
- 随机事件：可能发生也可能不发生的结果。常用字母 $ABC$、$A_1$、$A_2$...来表示。
- 基本事件：试验的每一个可能结果。常用$e,w$或$e_1,e_2...,w_1,w_2...$来表示。随机事件发生当且仅当组成的基本事件有一个发生。
- 样本空间：试验$E$的全部基本事件组成的集合，其中基本事件又被称为样本点。样本空间常记为$\Omega$或$S$。
- 样本空间的描述：与集合的描述相似，例如$S_1=\{e_1,e_2,...\}$，$S_2=\{0,1,2,...\}$，$S_3=\{h|1.5m<h<2m\}$。

#### **运算律：**

- 交换律：$A+B=B+A$，$AB=BA$
- 结合律：$(A+B)+C=A+(B+C)$，$(AB)C=A(BC)$
- 分配律：$(A+B)C=AC+BC$，$(AB)+C=(A+C)(B+C)$
- 德摩根公式：$\overline{\sum\limits_{i}A_i}=\prod\limits_{i}\overline{A_i}$，$\overline{\prod\limits_{i}A_i}=\sum\limits_{i}\overline{A_i}$

> 例：试将事件$A+B+C$表示为互不相容的事件之和。  
> 解：利用$A-B=A-AB=A\overline{B}$，$A+B=A+(B-A)=A+(B-AB)$或$A+B=(A-AB)+AB+(B-AB)$，得到
> $$ A+B+C=A+(B+C)=A+(B+C)\overline{A}=A+(B+C\overline{B})\overline{A}=A+B\overline{A}+C\overline{B}\overline{A} $$
