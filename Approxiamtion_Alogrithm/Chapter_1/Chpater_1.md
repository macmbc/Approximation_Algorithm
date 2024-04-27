# Exercise 1.2
## 问题描述

给定有向图 $G=(V,E),$满足边权值 $c_{ij}\geq 0$.存在一个根节点 $r\in V$和终端顶点集 $T\subseteq V$.目标找到一个最小树,满足 
$$
\forall i \in T,\exist 从r到i的有向路径
$$
证明:除非N=NP,否则对于常数c,该问题不存在$clog|T|$-近似算法.

