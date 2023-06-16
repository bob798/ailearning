# 张量|Tensor

## 程序员视角

TensorFlow是这么定义的：

> A tensor is a generalization of vectors and matrices to potentially higher dimensions.

简单翻译过来就是：**张量是多维数组，目的是把向量、矩阵推向更高的维度。**

![标量、向量、矩阵、张量的关系](https://easyai.tech/wp-content/uploads/2022/08/9768c-2020-02-13-4liang.png)

https://easyai.tech/ai-definition/tensor/

https://www.tensorflow.org/guide/tensor?hl=zh-cn

张量（tensor）是一个多维数组（multidimensional arrays），即一种存储数字集合的数据结构，这些数字可通过索引（index）单独访问，并可通过多个索引进行索引。

张量是将向量和矩阵推广到任意维数。如下图所示，一个张量的维数与张量中用来表示标量值的索引的数量一致

![img](https://yuanxiaosc.github.io/2019/11/28/%E7%90%86%E8%A7%A3%E5%BC%A0%E9%87%8F/%E5%BC%A0%E9%87%8F%E7%A4%BA%E6%84%8F%E5%9B%BE.png)

https://yuanxiaosc.github.io/2019/11/28/%E7%90%86%E8%A7%A3%E5%BC%A0%E9%87%8F/

## 数学专业视角

线性代数张量

# 张量

![Disambiguate.png](https://www.bananaspace.org/w/images/thumb/c/c4/Disambiguate.png/30px-Disambiguate.png)

本文介绍的是线性代数中的张量. 关于微分几何中的张量, 请参见 “[张量场](https://www.bananaspace.org/wiki/张量场)”.

**张量**是[向量](https://www.bananaspace.org/wiki/向量)的推广. 在 *n* 维[空间](https://www.bananaspace.org/wiki/向量空间)中, 一个向量 *v* 由 *n* 个分量 *v*1,…,*v**n* 构成, 而一个 **(****p****,****q****)****-张量** *a* 则由 *n**p*+*q* 个分量构成 (命题 [3.2](https://www.bananaspace.org/wiki/张量#3)), 这些分量通常记为*a**i*1,…,*i**p**j*1,…,*j**q*(*i*1,…,*i**p*,*j*1,…,*j**q*∈{1,…,*n*}).特别地, 向量也就是 (0,1)-张量.

严格地说, 张量是指某些特定的[张量积](https://www.bananaspace.org/wiki/张量积)中的元素. 例如, [向量空间](https://www.bananaspace.org/wiki/向量空间) *V* 上的 (*p*,*q*)-张量就是张量积 (*V*∗)⊗*p*⊗*V*⊗*q* 中的元素 (定义 [1.1](https://www.bananaspace.org/wiki/张量#1)). 换言之, (*p*,*q*)-张量大致就是 “吃掉 *p* 个向量, 就能吐出 *q* 个向量” 的对象 (命题 [3.1](https://www.bananaspace.org/wiki/张量#2)).

https://www.bananaspace.org/wiki/%E5%BC%A0%E9%87%8F

## 物理学视角

对应空间？

待完善

