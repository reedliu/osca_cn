# 我与《单细胞交响乐》的缘分

## 写在前面

Hi 大家好，我是[生信星球](https://jieandze1314-1255603621.cos.ap-guangzhou.myqcloud.com/blog/2020-05-09-035101.png)的”豆豆“，也是[简书](https://www.jianshu.com/u/d7b77c171c15)上的”刘小泽“。  
这是我的第一本开源书，之后也许会有第二本、第三本...持续学习，不断努力🤠 

本书的链接是：[https://jieandze1314.osca.top/](https://jieandze1314.osca.top/)

> 更新于2020-07-23

## 吸引

我是在 2019年10月注意到： [Orchestrating Single-Cell Analysis with Bioconductor](https://osca.bioconductor.org/)

原因很简单，当时个人对单细胞很感兴趣，并且这本书还是Bioconductor团队。大佬出品，必是精品。  
为了增加辨识度，我给这本书取了个名字：**单细胞交响乐**。因为单细胞数据涉及了许多复杂数据结构和流程，就像一个大乐团中的各种乐器，相互配合环环相扣才能演奏美妙的乐章。

开始也是抱着试学的态度，从最简单的基础学起。后来数据结构那一章真正吸引了我，将复杂的单细胞数据结构解释得浅显易懂，还在2019.10.26写了一篇推送：[送你个对象](https://mp.weixin.qq.com/s/-zvslOg39KGodaxJcQJYaQ)。

![](.gitbook/assets/image%20%281%29.png)

## 中断

我想大部分人接触单细胞数据，应该都是借助[CellRanger](https://support.10xgenomics.com/single-cell-gene-expression/software/pipelines/latest/what-is-cell-ranger)、[Seurat](https://satijalab.org/seurat/)流程学习的，也因此容易形成一个思维定势，说到scRNA分析，就想到Seurat这个R包。这本书的内容不太一样，它全篇都是基于自己的数据结构SingleCellExperiment，使用的R包也主要是自己团队开发的[Scater](http://bioconductor.org/packages/release/bioc/vignettes/scater/inst/doc/overview.html)、[Scran](https://bioconductor.org/packages/release/bioc/vignettes/scran/inst/doc/scran.html)包，并且用法和Seurat差距还蛮大的。

单细胞分析对于我来说一直只是一个爱好，暂时还没有实际项目的应用。有时心里就犯嘀咕：我为什么要花时间去学习两个用途差不多的包呢？用最流行的流程不就得了？

慢慢地，这本书在我心里的地位就下降了，后来也不再有热情去翻译、理解这本书了。

## 不舍

在放弃更新的一段时间，心中时常会有不舍和愧疚，想到了开头却没想到结尾。

每次看到别人分享这本书，我都会偷偷打开之前的交响乐文件夹，看看里面的几篇笔记，然后叹一口气，再次关上，心想：等我有时间了，一定要补上后面的！

然而，这一等，就是大半年...

## 重拾

> 2020是一个注定特殊的年份  
> 万万没想到，从6.23到7.22，经历了一个月，完成了这个长久的小心愿

2020年的6月，无意间又打开了这本书的链接，看着团队已经更新到了30多章，此时”花花“（也就是域名jieandze1314中的jie）也开始了单细胞的学习，我答应她要提供一份学习资料。正好借着公众号推出的专辑功能，我尝试每写一篇都发表然后放在[公众号专辑](https://mp.weixin.qq.com/mp/appmsgalbum?action=getalbum&__biz=MzU4NjU4ODQ2MQ==&scene=1&album_id=1402375646780817409#wechat_redirect)中，当做对自己的一个提醒。

第一篇发表于2020-06-23，接下来的几天，我都保持了每天阅读一章、重复一遍、更新一篇的节奏。当然，开始的速度会很慢，但随着对整体数据结构以及R包、函数的了解越来越深入，我也能明白作者想要做什么事，又是如何去实现的，后来速度就快了许多。这里必须要感谢Bioconductor团队精心准备了各种测试数据集和详细的操作代码。

为了提供更好的阅读、交流体验，我将之前的学习笔记做成了现在这本开源书。个人认为，开源书比出版书的优势就是：持续更新；方便沟通；易于更改。

与原著作者交流了一下，他们表示还会继续更新，当然我也会一直保持同步。  
此外，我希望这本书不仅仅是中文翻译版，还希望能加入更多其他比较重要的知识，比如Seurat的各种操作、上游操作流程等等，让本书内容更加丰富。

## 致谢

> 为了表达对作者的敬意，在本书上线前，特意征求了作者的同意  
> 感谢他们对Bioconductor社区的贡献

* _**Aaron Lun, PhD**_
* _**Robert Amezquita, PhD**_
* _**Stephanie Hicks, PhD**_
* _**Raphael Gottardo, PhD**_

**技术一直进步，学习从未停止。这本书也许不会有完结篇，只有~未完待续**🤓 ~

