# 你一直想知道的关于合成数据的一切

> 原文：<https://pub.towardsai.net/everything-you-always-wanted-to-know-about-synthetic-data-c0baf473550c?source=collection_archive---------0----------------------->

## 你不需要再有没有答案的问题了

![](img/2f3eafcb48ac24acb2c3dda7452fd933.png)

我听到了。(图片由来自 [Pexels](https://www.pexels.com/photo/man-in-red-polo-shirt-sitting-near-chalkboard-3779448/?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels) 的 [Andrea Piacquadio](https://www.pexels.com/@olly?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels) 拍摄)

"所以这个软件包从实际数据中创造了大量的虚假数据？"

“你可以这么说——但这叫做合成数据。”

“但这有什么意义呢？会很吵。为什么不用实际数据本身呢？”

“我们可以，但是没有足够的数据。此外，在使用实际数据时还存在隐私问题。”

“哦，所以你是说这种合成数据与实际数据相似，而没有泄露私人信息？”

麻省理工科技评论[指出](https://www.technologyreview.com/2022/02/23/1044965/ai-synthetic-data-2/)合成数据将是 2022 年的突破性技术之一。Gartner 声称，没有合成数据，我们无法想象构建卓越价值的人工智能模型。

根据 Unity AI 高级副总裁的说法，合成数据实际上比真实数据更好，我们可以通过合成数据来丰富真实数据。

尽管在合成数据上有一些功劳，但我有过许多类似的对话，人们并不知道合成数据。这不仅仅是一个“时髦词”——在这篇文章中，我希望阐明合成数据到底是什么。

我整理了来自朋友、同事、开源社区和 LinkedIn 的问题，并试图回答关于合成数据的最常见问题。

我们开始吧。

## 1.什么是合成数据？

合成数据是人工生成的数据，不是从现实世界的事件中收集的。

在确保数据中的人的隐私的同时，合成数据是实际数据的统计复制品。

## 2.为什么我们需要关心合成数据？

又回到了现在大部分 AI 公司面临的问题。

麦肯锡表示，要在数字化转型中超越竞争对手，高质量的数据是关键。在采访了数百名数据科学家后， [YData 得出结论](https://medium.com/ydata-ai/what-we-have-learned-from-talking-with-100-data-scientists-d65ed2475f4b)，高质量数据的不可用性是数据科学家面临的最大问题之一。

根据 VentureBeat 在 [Transform 2019](https://venturebeat.com/2019/07/19/why-do-87-of-data-science-projects-never-make-it-into-production/) 上的数据，87%的数据科学项目永远不可能在生产环境中使用。2017 年《哈佛商业评论》[研究](https://hbr.org/2017/09/only-3-of-companies-data-meets-basic-quality-standards)显示，只有 3%的公司数据达到了数据质量的最低标准。

[Gartner 估计](https://blogs.gartner.com/andrew_white/2021/07/24/by-2024-60-of-the-data-used-for-the-development-of-ai-and-analytics-projects-will-be-synthetically-generated/)到 2024 年，合成数据将占数据科学和分析项目所用数据的 60%左右。

同样，大量研究得出结论，人工智能发展的瓶颈是大规模的高质量数据，合成数据是解决方案之一。

因此，消除开发人员、数据科学家、公司和学术研究人员使用合成数据的门槛比以往任何时候都更加重要。

## 3.你如何创建合成数据？

可以使用几种技术来生成基于用例的合成数据。

对于没有实际数据可用的情况，但当数据科学家全面了解数据的性质时，基于规则的合成和基于已知分布生成数据将起作用。在这两种技术中，可以生成符合规则或分布的随机样本。

当实际数据可用时，生成模型，特别是变分自动编码器(VAEs)和生成对抗网络(GANs)已经在该领域获得了很多关注。

[GAN 是一个强大的工具](https://medium.com/ydata-ai/generating-synthetic-tabular-data-with-gans-part-1-866705a77302)，用于生成与真实数据集难以区分的人工数据集。在 GANs 中，当生成器网络获取随机样本数据以生成合成数据集时，鉴别器根据真实数据集对其进行评估。这个模型训练过程迭代发生。

[VAE 是一种无监督算法](https://towardsdatascience.com/understanding-variational-autoencoders-vaes-f70510919f73)，其中编码器网络学习并压缩原始数据集，然后解码器网络从压缩中生成合成数据。

当我写这篇文章时，合成数据是人工智能中一个活跃的研究主题，不同的新方法正在迅速发展。

## 4.你如何知道你创建的合成数据与原始数据相似？

至关重要的是根据三个关键基准评估生成的合成数据和原始数据:效用、保真度和隐私。

**效用**表示合成数据在下游应用中与原始数据集相比的性能，**保真度**测量合成数据在统计上与原始数据匹配的程度，**隐私**表示合成数据的保密级别。

虽然探索性统计比较、相关性得分和直方图相似性得分有助于了解保真度、特征重要性得分和预测得分，但在合成数据上进行训练和在真实数据上进行测试有助于评估数据的效用。我们可以通过精确匹配分数、邻居的隐私分数和成员推断分数来评估隐私。

这些指标通常在综合后自动生成报告。这里是[一个实现，带有针对合成数据的一些标准评估指标的示例](https://github.com/Vicomtech/STDG-evaluation-metrics)。根据结果，我们可以用不同的参数重新生成它，直到我们对生成的数据质量感到满意为止。

然而，必须做出某些妥协，因为不可能在三个基准测试中的每一个上获得最佳结果，因为它们之间存在相反的关系(稍后将详细介绍)。)

## 5.创建的合成数据如何处理偏差？

在收集数据、处理数据或建立模型时，可能会向数据中注入偏差。

数据收集中的偏差很难解决，因为整个收集过程必须重新设计，而不是在综合数据时固定不变。根据定义，合成数据不会给现有的原始数据添加或注入新的偏见。

有了足够的领域知识，可以处理偏差，同时数据的合成和合成数据生成评估的过程使这种偏差处于检查之下。

## 6.创建合成数据的成本高吗？涉及哪些成本？

这是一个主观问题，答案会根据您的使用案例和您需要的数据规模而有所不同。

有几个可用的开源存储库；因此，唯一的成本是获得原始数据集和计算资源的成本。或者，如果您在生产就绪的业务用例中需要合成数据，您也可以联系专门研究合成数据的公司。

## 7.我们能出售合成数据并将其货币化吗？

一般来说，合成数据不是从真实世界收集的，这意味着它最有可能被货币化。

然而，这可能取决于用例。

## 8.合成数据与其他隐私保护技术相比有多大不同？

您可能听说过隐私保护技术，如同态加密、联合学习和差分隐私。

[联合学习](https://blog.openmined.org/what-is-federated-learning/)通过向数据发送模型，在边缘实现训练，而数据永远不会离开数据源。[同态加密](https://blog.openmined.org/what-is-homomorphic-encryption/)实现对加密数据的计算。

这些算法有各种各样的用例，例如，当涉及到大数据的私人分析时— [差分隐私](https://blog.openmined.org/differential-privacy-by-shuffling/)是一条路要走。

生成的合成数据可以是不同的私有数据，最适合于数据科学家需要与常见数据科学问题的原始数据粒度相同的数据。

## 9.合成数据的局限性是什么？

虽然我们可以生成与实际数据相似的数据，但合成数据有一定的局限性。

最重要的限制之一是隐私和效用之间的权衡。一个可靠的保护隐私的数据生成导致合成数据的效用的必要妥协，以利于获得隐私。因此，隐私和效用成反比。

面临的挑战是为手头的每个特定用例找到实用和隐私之间的最佳平衡。

此外，数据中可能存在一些硬约束。例如，销售值总是等于单价和销售量的乘积。然而，当优先考虑合成过程的实用性和私密性时，这些特定于域的约束可能会受到损害。

## 10.如何开始使用合成数据？

很高兴你有这个问题。最好的开始方式是加入一个免费的开源社区，从事这样的项目:[以数据为中心的人工智能社区](https://datacentricai.community/)因为你不会独自一人计算合成数据。

如果你有一些技术背景，你可以亲自动手操作开源库(例如， [ydata-synthetic](https://github.com/ydataai/ydata-synthetic) ，因为我在这里已经有所贡献)。一般来说，这些库有[大量的例子](https://github.com/ydataai/ydata-synthetic/tree/dev/examples/regular)让你入门。

如果你是一名数据科学家，你也可以使用像生成对抗网络这样的算法从头开始创建合成数据。[法比亚娜·克莱门特](/how-to-generate-synthetic-data-4ae4ff156344)为你提供了一份关于如何做到这一点的详细指南。

我希望这篇文章回答了你关于合成数据的大部分迫切问题。尽管我试图尽可能多的回答——你可能还有一些问题。

这是一个不断发展的话题，所以它必然是先进的，但可解释的。

所以，请不要感到害羞。在回复部分提出你的问题，或者加入[以数据为中心的人工智能社区](https://datacentricai.community/)，直接向专家提问。

不管怎样，我都非常乐意回答这些问题，并进一步扩展这篇文章。快乐学习！