---
description: 刘小泽写于2021.8.24
---

# scRNA已经开发出超过1000款工具了，你用过几种？

## 速览

* 题目：Over 1000 tools reveal trends in the single-cell RNA-seq analysis landscape
* 日期：2021.8.14
* 链接：[https://www.biorxiv.org/content/10.1101/2021.08.13.456196v1](https://www.biorxiv.org/content/10.1101/2021.08.13.456196v1)
* 工具列表：[https://www.scrna-tools.org/tools](https://www.scrna-tools.org/tools)

## 图1

![](https://jieandze1314-1255603621.cos.ap-guangzhou.myqcloud.com/blog/2021-08-24-083308.png)

* 这个网页从2016年开始搜集scRNA的分析工具，截止到2021.8.12，搜集了1027款
* 从2018年开始，增速明显，按这个趋势到**2022年预计会有1500款，2025年会有3000款**
* 大约三分之二的工具至少有一篇peer-review的文章，四分之一有预印本
* 可视化、降维聚类是工具开发的前沿阵地，像是多样本整合、轨迹推断也逐渐成为了标准流程，不过更高级的分析比如罕见细胞类型鉴定、可变剪切工具还较少
* 目前的多面手主要是seurat、scanpy，更多的工具主要集中在某一种或某几种分析

## 图2

![](https://jieandze1314-1255603621.cos.ap-guangzhou.myqcloud.com/blog/2021-08-24-084554.png)

* R工具目前还是居多，但越来越多的工具采用python开发，而基于R的开发数量正在下降；因为单细胞数据量和复杂度都在逐步提高，而性能方面的优势使得python逐渐提升
* 另一个因素在于：曾经的bulk RNASeq一般都是生命科学领域的研究人员关注，解决的也是生物问题；而scRNA具有更高的探索性，因此有时在降维聚类等方面需要结合机器学习这种更加复杂的统计方法，所以计算科学领域的研究人员也逐渐加入，而python也是他们所常用的机器学习工具
* 按这个速度推断，**2025年中期python就会超过R**，成为scRNA数据分析领域最为热门的语言
* B图中可以看到红线上方的**”潜力股工具“：integration和classification**。早期受到测序条件和经费的限制，可能一个实验只能做一个样本或者很少几个样本，但现在**大样本量逐渐成为趋势**（比如最大的Human Cell Atlas），因此如何整合以及处理批次效应，就成了一个重点
* 随着研究逐渐深入，样本整合越来越多，细胞类型的细分也成为趋势，比如下面这一张。之前细胞类型的推断可能更偏向于根据表达量计算距离，后来的方案则更好地利用了公共参考数据库的资源辅助推测（比如SingleR中就包含了一些内置数据集，大部分是bulk RNA-Seq或芯片数据中经过筛选的细胞类型） ![image-20210824170550144](https://jieandze1314-1255603621.cos.ap-guangzhou.myqcloud.com/blog/2021-08-24-090550.png)

## 图3

![](https://jieandze1314-1255603621.cos.ap-guangzhou.myqcloud.com/blog/2021-08-24-091304.png)

* github成为scRNA工具开发的主阵地（超过90%），包括709个owner的960+个仓库，有超过1700个贡献者**提交了超过150,000次**
* 可以看到，scRNA的文章预印本呈现增长趋势，方便更多的工具提前问世，让读者更快地提交issue帮助改进

