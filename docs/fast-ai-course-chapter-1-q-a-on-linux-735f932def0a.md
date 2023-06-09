# Fastai 课程第一章 Linux 问答

> 原文：<https://pub.towardsai.net/fast-ai-course-chapter-1-q-a-on-linux-735f932def0a?source=collection_archive---------3----------------------->

## 系列:[人工智能](https://towardsai.net/p/category/artificial-intelligence)

## 本章末尾的问卷答案

![](img/c2ea0260e90e31a535f97c21089c9579.png)

图片由[泰勒·拉斯托维奇](https://unsplash.com/@lastly)拍摄

教科书的第一章提供了人工智能的广泛概述。它涵盖了一些先决条件，应用，里程碑，术语，和主题的机制。它还演示了用于加载数据集、训练模型和进行预测的代码。

> 我们花了很多周时间写问卷。这样做的原因是，因为我们试图思考我们希望你从每一章中学到什么。因此，如果您先阅读调查问卷，您可以了解我们认为您在继续下一章之前应该了解的内容，因此，请确保在继续下一章之前完成调查问卷。
> 
> —杰瑞米·霍华德，Fast.ai

## 1.深度学习需要这些吗？

## 很多数学？

不，深度学习[入门不需要高等数学](#4f68)。它由大多数深度学习库在后台处理。它也只在需要使用[线性代数](#3cfa)、[多变量微积分](#6ae5)和[概率](#942a)和[统计](#af38)的微调模型中变得必要。

## 大量数据？

不会，当数据质量较高时，小型数据集可以产生与大型数据集相似的结果。这取决于数据是否准确、完整、相关、有效、及时和一致。使用[半监督学习](#dd24)、[数据扩充](#a547)、[微调](#9e89)和[差分学习率](#fc88)也有帮助。

## 很多昂贵的电脑？

不，不需要一台昂贵的计算机就可以开始深度学习。可以使用云服务免费学习，如 [Gradient](#c047) 、 [Colab](#6639) 和 [Kernels](#4038) ，这些云服务提供了对高性能显卡的访问。由于可用性波动，它还可能会有延迟和性能变化。

## 博士学位？

不，学习和应用深度学习并不需要博士学位。它培养学生在学术环境中成为多产的学者和研究人员。它还在很大程度上专注于改进用于深度学习的理论和/或工具，这需要对数学有很强的理解。

## 2.说出深度学习现在是世界上最好的五个领域:

自然语言处理(NLP)是人工智能的一个分支，旨在赋予计算机理解文本和口语的能力。它将计算语言学与统计、机器学习和深度学习模型相结合。它还使计算机能够以文本或语音数据的形式处理人类语言，并理解其全部含义，包括说话者或作者的意图和情感。

*计算机视觉*是人工智能的一个分支，致力于赋予计算机从数字图像、视频和其他视觉输入中获取有意义信息的能力。它使计算机能够从一幅图像或一系列图像中提取、分析和理解有用的信息。它还使计算机能够使用这些信息来自动执行任务，如采取行动、做出决定或提出建议。

*图像生成*是人工智能的一个分支，致力于赋予计算机创造新材料的能力，如图像、音乐、语音和文本。它使计算机能够使用相互竞争的独立神经网络来创造新材料并检测其真实性。它还不断地学习制造更好的材料和更好的检测，直到新材料被认为是真实的，从而产生最终的输出。

*医学*是人工智能的一个分支，致力于赋予计算机分析、理解和呈现复杂医疗数据的能力。它使计算机能够协助诊断过程、治疗方案开发、药物开发、精确医疗以及患者监测和护理。它还使计算机能够分析来自电子健康记录的大量数据，用于疾病预防和诊断。

生物学是人工智能的一个分支，致力于赋予计算机调查、分析和分类生物数据的能力。它使计算机能够协助细胞图像分类、基因组医学、生物标记开发和药物发现。它还使计算机能够使用关于一个人的全面生物信息来预测和诊断疾病，并确定或开发最佳疗法。

## 3.基于人工神经元原理的第一个设备叫什么名字？

Mark I 感知器被认为是有史以来第一个人工神经网络。它是由 Frank Rosenblatt 于 1957 年开发的，用于图像分类。它在物理上也由一系列随机连接到关联单元的感觉单元组成，关联单元的重量记录在电位计中，并由电子马达调节。

![](img/a9711cf13444ac854370322e0f700947.png)

图片来自[车主手册](https://apps.dtic.mil/dtic/tr/fulltext/u2/236965.pdf)

## 4.基于同名书，并行分布式处理(PDP)有什么要求？

*并行分布式处理(PDP)* 是心理学中用来解释认知过程的模型。它提出认知过程源于大量神经元之间通过突触连接的相互作用。它还提出，控制加工的知识储存在连接的强度中，并通过经验逐渐获得。

*   *一组处理单元*
*   *激活状态*
*   *每个单元的输出功能*
*   *单元之间的连接模式*
*   *用于通过连接性网络传播活动模式的传播规则*
*   *一个激活规则，用于将撞击一个单元的输入与该单元的当前状态相结合，以产生该单元的新激活级别*
*   *通过经验修改连接模式的学习规则*
*   系统必须运行的环境

## 5.阻碍神经网络领域发展的两个理论误解是什么？

第一个理论误解是神经网络不能对非线性模式进行分类。这是基于《感知器》一书，该书证明了单层感知器无法对非线性模式进行分类。它还推测，多层感知器可能会克服这一限制，但它仍然被错误地作为反对神经网络的证据。

第二个理论上的误解是神经网络太大太慢，没有用。这是基于他们难以共事的名声和与新的两层感知器相比表现不佳。它也发生在多层感知器被证明有效之后，但在人们知道神经网络由于当时数据集、计算能力和算法不足而受到限制之前。

## 6.什么是 GPU？

*图形处理单元(GPU)* 是一种专用处理器，用于加速图形渲染。它可以处理数以千计的单一任务，如在电脑游戏中显示三维环境。它运行神经网络的速度也比中央处理器快几百倍。

## 7.打开一个笔记本，执行一个包含:`1+1`的单元格。会发生什么？

![](img/1aae8ce4774a2fee22a4c5005cba0f0c.png)

答:打印方程式的结果

## 8.按照本章笔记本的精简版的每个单元格进行操作。在执行每个单元格之前，猜猜会发生什么。

这个笔记本的精简版包含可执行代码，没有教科书中的文本。可以在文章的附录中看到，其中包含了分别显示代码和结果的截图。它也可以在位于`clean`子目录下的`01_intro.ipynb`文件中找到。

*   [查看截图](#b741)

## 9.完成 Jupyter 笔记本在线附录。

*Jupyter Notebook Online 附录*是在 Fast.ai 中使用的笔记本文件，用于向学生介绍 [Jupyter Notebook](#5b02) 。它有解释、说明和截屏，显示如何使用用户界面、markdown 格式、键盘快捷键和代码功能。它还有两个版本，分别存储在`root`目录和`clean`子目录中的`app_jupyter.ipynb`。

![](img/155a67446c550ff35e719f354e887828.png)

## 10.为什么很难使用传统的计算机程序来识别照片中的图像？

开发一个传统的计算机程序来识别照片中的图像是非常困难的。这需要识别流程中涉及的每一步，并将这些步骤翻译成代码。也不清楚人类大脑如何识别图像，这使得识别步骤变得更加困难。

## 11.塞缪尔说的“重量分配”是什么意思？

*权重分配*是 Arthur Samuel 用来描述当前分配给人工神经网络中[权重](#d55d)的值的术语。它可以被认为是另一种输入，因为这些值会影响模型并决定它如何运行。它还产生一个可测量的性能，可以自动测试并通过调整值来改进。

## 12.我们通常在深度学习中使用什么术语来表示塞缪尔所谓的“权重”？

*模型参数*是机器学习中使用的变量，用于存储模型用来进行预测的权重或偏差。它包含在训练过程中使用优化算法自动估计的值，并作为训练模型的一部分保存。它还定义了模型在依赖于数据集的不可见数据上的表现。

## 13.画一张图，概括塞缪尔对机器学习模型的看法。

![](img/c28f03ea0e4bdcad906a9eec4fc31df3.png)

详细训练循环

## 14.为什么很难理解为什么深度学习模型会做出一个特定的预测？

深度学习模型可能有成百上千层，这使得很难确定哪些因素在决定最终输出方面很重要。它还可以有多达数千甚至数十亿个彼此交互的模型参数，这使得更难理解为什么深度学习模型会做出特定的预测。

## 15.证明神经网络可以以任何精度解决任何数学问题的定理叫什么？

*通用逼近定理*是一种理论，暗示当给定适当的权重时，人工神经网络可以表示广泛的有趣函数。它指出，具有包含足够但有限数量的神经元的一个隐藏层的前馈神经网络应该能够以合理的精度逼近任何连续函数。

## 16.你需要什么来训练一个模特？

*训练*是机器学习中的一个过程，用于建立一个可以对未知数据做出准确预测的模型。它涉及架构、[数据集](#1999)、超参数、损失函数和[优化器](#b806)。它还包括将数据集分成[训练](#5f32)，验证和测试数据，对数据进行预测，计算损失，并更新权重。

## 17.反馈回路如何影响预测性警务模式的推出？

[预测监管](#6f2d)模型是使用历史犯罪数据创建的，历史犯罪数据代表记录在案的犯罪，而不是所有犯罪。它包含了来自历史犯罪数据的偏见，这严重影响了关于将警务活动集中在哪里的预测。这也导致在那些地区更多的逮捕，从而延续了[正反馈循环](#2b05)。

## 18.对于猫识别模型，我们必须总是使用 224×224 像素的图像吗？

不，但是图像尺寸的改变是有限制的。如果图像太小，则会产生错误，这发生在神经网络在向前传播期间减小维度时用完数据的时候。如果图像太大，当没有足够的层来学习不同的过滤器时，它也不能获得合理的精度。

## 19.分类和回归有什么区别？

*分类*是监督学习的一个子类，用于将看不见的数据分类为两个或更多类别中的一个。它将分类算法应用于训练数据集，以识别每个类别的共有特征。它还将特征与未知数据进行比较，并预测数据属于每个类别的概率。

*回归*是监督学习的一个子类，用于预测连续值。它将回归算法应用于训练数据集，以确定最能代表变量之间关系的直线或曲线。它还预测当其他自变量保持固定时，因变量相对于自变量如何变化。

## 20.什么是验证集？什么是测试集？我们为什么需要它们？

*验证集*是一个数据集，用于机器学习，以提供模型的无偏评估并调整模型超参数。它包含总数据集的大约 10–20 %,用于确定模型是正确识别新数据还是过度拟合。它还包括用于监督学习的标签和注释。

*测试集*是在机器学习中使用的数据集，用于在模型完全训练后提供最终的无偏评估。它包含总数据集的大约 10–20 %,用于进一步确定模型是正确识别新数据还是过度拟合。它还包括用于监督学习的标签和注释。

训练过程需要验证集来防止过度拟合。它在每个时期后测试模型的性能，以确定性能因过度拟合而下降的地方，并调整超参数以进一步提高性能。它还需要测试集来测试模型在未知数据上的性能，以提供对它在生产中的表现的估计。

## 21.如果不提供验证集，fastai 会怎么做？

它使用总训练数据的 20%自动创建验证集。

![](img/7560e965055d8fc4514083f76ab962a7.png)

## 22.我们可以总是使用随机样本进行验证吗？为什么或为什么不？

不，时间序列预测不适用于随机样本。它需要将数据分成不同的时间段，其中大部分数据用作训练的历史数据，只有最近的数据用作验证的未来数据。这也会导致过于乐观的结果，因为[随机抽样](#2647)使用过去和未来的数据进行验证。

## 23.什么是过度拟合？举个例子。

*过度拟合*是机器学习中的一个错误，当模型在训练数据上表现良好，但在看不见的数据上却不能很好地推广时，就会发生这种错误。它可能是过度训练、缺乏验证或不正确的验证、重量调整和优化尝试的结果。也可能是使用包含无意义信息的训练数据的结果。

![](img/8d3cb6559562f11006ea602578201a00.png)

## 24.什么是度量？和“损失”有什么区别？

*评估指标*是机器学习中用来测试模型性能的函数。它可以测量具有平衡数据集的模型的准确度、精确度和召回率，或者具有不平衡数据集的模型的曲线下面积和接收器操作特征。它还会返回误导性的结果，这就是为什么要使用多个指标的原因。

*损失函数*是一个在机器学习中使用的函数，用于评估算法在给定数据上的表现。它计算每个训练迭代的损失，该训练迭代测量预测值和实际值之间的数学距离。它还用于计算训练过程中更新权重所需的梯度。

## 25.预训练模型有什么帮助？

*预训练模型*是在机器学习中用来执行特定任务的模型。它已经用包含表示数据集特征的权重和偏差的大型数据集进行了训练。还可以使用迁移学习对其进行重新训练，以执行类似的任务，迁移学习产生的模型精度更高，需要的数据、时间和资源更少。

## 26.模特的“头”是什么？

*头*是机器学习中的一个类比，用于表示人工神经网络的[输出层](#1057)。它将模型解释为一个主干加一个头，主干指的是模型的架构，头指的是架构的最后一层。它还将迁移学习解释为替换预先训练的主干的头部。

## 27.CNN 早期的几层有哪些特征？后面几层呢？

卷积神经网络的早期层用于检测图像中的低级特征。它学习在第一层中检测边缘和颜色，这成为在第二层中检测由边缘和颜色的组合制成的纹理的构建块。它还继续学习如何检测每一层的更复杂的特征。

卷积神经网络的后续层用于检测图像中的高级特征。它学会检测复杂的图案，这些图案类似于在眼睛、耳朵和鼻子等物体中发现的纹理。它还最终学习如何检测诸如人和动物之类的对象，这成为从数据集中检测特定对象的构建块。

## 28.图像模型只对照片有用吗？

不可以，非图像数据只要转换成图像，就可以用图像模型分类，达到高精度。它可以通过将相似的要素放在一起并将不相似的要素放得更远来绘制数据，从而对相邻要素进行分组。它还可以揭示数据中隐藏的模式和/或特征集之间的关系。

## 29.什么是“建筑”？

*架构*是在机器学习中用来构建神经网络的模板。它定义了神经网络中使用的层数、大小和类型，该神经网络表示用于训练模型的数学函数。它还可以表示用于监督、非监督、混合或强化学习的任何类型的神经网络。

## 30.什么是细分？

*图像分割*是机器学习中的一个过程，用于将图像划分为包含具有相似属性的像素的不同区域。它可以定位图像中的对象，并对代表特定对象的每个像素进行颜色编码。它还可以对属于某一类的每个像素进行颜色编码，或者对属于同一类的对象的每个实例进行颜色编码。

## 31.`y_range`是做什么用的？我们什么时候需要它？

*Y 范围*是 Fast.ai 中使用的一个参数，用于指示框架预测数值而不是类别值。它限制了在对数据进行标准化回归时因变量的预测值。它还手动指定最大值和最小值，强制模型输出该范围内的值。

## 32.什么是“超参数”？

*超参数*是机器学习中使用的一个变量，用于调整模型以做出准确的预测。它为学习速率、时期数、隐藏层和控制训练过程的激活函数等参数设置一个值。它还必须在训练开始前手动设置，这会显著影响模型的性能。

## 33.在组织中使用人工智能时，避免失败的最佳方法是什么？

将人工智能引入组织时，避免失败的最佳方式是理解并使用验证和测试集。通过留出一些与提供给外部供应商或服务提供商的数据分开的数据，它可以大大降低失败的风险。它还让组织用测试数据评估模型的真实性能。

> “希望这篇文章能帮助您获得👯‍♀️🏆👯‍♀️，记得订阅获取更多内容🏅"

## 后续步骤:

本文是帮助您从头到尾设置完成 Fast.ai 课程所需的一切的系列文章的一部分。它包含在教科书每章末尾提供问卷答案的指南。它还包含使用术语和命令的定义、说明和屏幕截图一步一步地浏览代码的指南。

```
**Linux:**
01\. [Install the Fastai Requirements](https://medium.com/p/116415a9df22)
02\. [Fastai Course Chapter 1 Q&A](https://medium.com/p/735f932def0a)
03\. [Fastai Course Chapter 1](https://medium.com/p/d69df3db69a7)
04\. [Fastai Course Chapter 2 Q&A](https://medium.com/p/af9dab3ce8c6)
05\. [Fastai Course Chapter 2](https://medium.com/p/42d7a406349)
06\. [Fastai Course Chapter 3 Q&A](https://medium.com/p/2df7f3a9711)
07\. Fastai Course Chapter 3
08\. [Fastai Course Chapter 4 Q&A](https://medium.com/p/90d2ccb6eaa9)
```

## 其他资源:

本文是帮助您设置开始使用人工智能、机器学习和深度学习所需的一切的系列文章的一部分。它包含扩展的指南，提供术语和命令的定义，帮助您了解正在发生的事情。它还包含简明指南，提供说明和屏幕截图，帮助您更快获得结果。

```
**Linux:**
01\. [Install and Manage Multiple Python Versions](https://medium.com/p/916990dabe4b)
02\. [Install the NVIDIA CUDA Driver, Toolkit, cuDNN, and TensorRT](https://medium.com/p/cd5b3a4f824)
03\. [Install the Jupyter Notebook Server](https://medium.com/p/b2c14c47b446)
04\. [Install Virtual Environments in Jupyter Notebook](https://medium.com/p/1556c8655506)
05\. [Install the Python Environment for AI and Machine Learning](https://medium.com/p/765678fcb4fb)**WSL2:**
01\. [Install Windows Subsystem for Linux 2](https://medium.com/p/cbdd835612fb)
02\. [Install and Manage Multiple Python Versions](https://medium.com/p/1131c4e50a58)
03\. [Install the NVIDIA CUDA Driver, Toolkit, cuDNN, and TensorRT](https://medium.com/p/9800abd74409) 
04\. [Install the Jupyter Notebook Server](https://medium.com/p/7c96b3705df1)
05\. [Install Virtual Environments in Jupyter Notebook](https://medium.com/p/3e6bf456041b)
06\. [Install the Python Environment for AI and Machine Learning](https://medium.com/p/612240cb8c0c)
07\. [Install Ubuntu Desktop With a Graphical User Interface](https://medium.com/p/95911ee2997f) (Bonus)**Windows 10:**
01\. [Install and Manage Multiple Python Versions](https://medium.com/p/c90098d7ba5a)
02\. [Install the NVIDIA CUDA Driver, Toolkit, cuDNN, and TensorRT](https://medium.com/p/55febc19b58)
03\. [Install the Jupyter Notebook Server](https://medium.com/p/e8f3e9436044)
04\. [Install Virtual Environments in Jupyter Notebook](https://medium.com/p/5c189856479)
05\. [Install the Python Environment for AI and Machine Learning](https://medium.com/p/23c34b2baf12)**MacOS:** 01\. [Install and Manage Multiple Python Versions](https://medium.com/p/ca01a5e398d4)
02\. [Install the Jupyter Notebook Server](https://medium.com/p/2a276f679e0)
03\. [Install Virtual Environments in Jupyter Notebook](https://medium.com/p/e3de97491b3a)
04\. [Install the Python Environment for AI and Machine Learning](https://medium.com/p/2b2353d7bcc3)
```

## 词汇表:

*深度学习(DL)* 是机器学习的一个子类，它使用特殊的算法来学习如何越来越准确地执行特定的任务。它有四种学习方法，包括监督、半监督、无监督和强化学习。它还基于包含两个或更多隐藏层的[人工神经网络](#9d4d)生成模型。
[返回](#1021)

*人工神经网络(ANN)* 是一种机器学习算法，用于模仿人脑处理信息的方式。它包含组织成层的互连节点，这些层包括输入层、零个或多个隐藏层以及输出层。它还通过使用输入、权重、偏差和输出将数据发送到各层来处理数据。
[返回](#4f68)

*线性代数*是数学的一个分支，涉及向量、矩阵和线性变换。它处理数据集并执行数据预处理、数据转换、降维以及模型评估。它还被大量用于机器学习、深度学习、自然语言处理和推荐系统等领域。
[ [返回](#1021)

*多变量微积分*是微积分的延伸，涉及导数、积分和梯度。它处理多个变量，并确定变化率、曲线下面积和函数斜率。它还被大量用于机器学习优化，通过最小化损失函数来提高模型的性能。
[返回](#1021)

概率是数学的一个分支，它是关于一个事件发生的可能性和一个命题为真的可能性的数字描述。它包括量化、管理和利用不确定性。它还被用于模式识别、模型训练、算法创建、超参数优化和模型评估的机器学习。
[返回](#1021)

*统计*是一个与汇总数据和从数据样本中得出结论有关的领域。它处理大量数据，包括数据收集、分析、解释和展示。它还被用在机器学习中，用于开发模型，这些模型理解并量化它们自己对未来未知数据的预测准确性。
[回车](#1021)

*半监督学习*是一种机器学习算法，它使用少量的已标记数据和大量的未标记数据来教会自己更好地执行任务。它从已标记的数据中产生一个模型，用于预测未标记的数据。然后，它使用标记和预测的数据来产生更准确的模型。
[ [返回](#81e2)

*数据扩充*是一种在机器学习中使用的技术，通过创建数据集中图像的修改版本来人为增加训练数据集的大小。它可以包括翻转、旋转、缩放、填充、裁剪、平移和变换图像。它还可以帮助防止在训练机器学习模型时过度拟合。
[ [返回](#81e2) ]

*微调*是一种用于迁移学习以减少训练时间和提高准确性的技术。它重新使用以前训练的模型的部分来执行不同但相似的任务，方法是删除其最后一层并用新层替换它来进行预测。它还可以使用更小的数据集来训练整个神经网络、最后几层或最后一层。
[ [返回](#81e2)

*差异学习率*是迁移学习中使用的一种技术，用于减少训练时间和提高准确性。它将网络分成多层组，并为每组设置不同的学习速率。它还使用最低的学习率训练初始层，并根据数据集与预训练模型的相似程度逐渐增加后面层的学习率。
[返回](#81e2)

*Gradient* 是由 Paperspace 托管的云服务，允许开发人员大规模开发、培训和部署他们的深度学习模型。它使用专门版本的 Jupyter Notebook，预装了深度学习库、云存储和版本控制管理。它还有免费的显卡，可以一次运行笔记本长达 12 小时。
[返回](#7937)

*协同实验室(Colab)* 是一项由谷歌托管的云服务，允许开发者通过他们的网络浏览器编写和执行 Python 代码。它使用专门版本的 Jupyter Notebook，预装了深度学习库、云存储和 GitHub 集成。它还有免费的显卡，可以一次运行笔记本长达 12 小时。
[回车](#7937)

*Kernels* 是由 Kaggle 托管的云服务，允许开发人员参加竞赛并参与其数据科学社区。它使用专门版本的 Jupyter Notebook，预装了深度学习库、云存储和数据集。它也有免费的显卡，可以一次运行笔记本长达 6 小时或一周 30 小时。
[ [返回](#7937)

Jupyter Notebook 是一个用于创建、修改和分发包含代码、等式、可视化和叙述性文本的笔记本的程序。它提供了一个在 web 浏览器中运行的交互式编码环境。它也已经成为机器学习和数据科学的首选工具。
[ [返回](#53a7) ]

*权重*是一个随机数，在机器学习中用来识别一个特征对预测的影响有多大。它与输入相乘，以转换在人工神经网络隐藏层的两个节点之间传递的数据。它还会在训练过程中得到更新和优化，以提高未来预测的准确性。
[ [返回](#4ca7)

*数据集*是在机器学习中使用的数据集合，用于创建一个以非常高的精度执行特定任务的模型。它通常包含带注释的文本、音频、图像或视频，在训练过程中被分成训练、验证和测试数据集。它还根据数据的质量和数量来确定模型的性能。
[返回](#85ae)

*优化器*是机器学习中用来更新模型参数以最小化损失函数的函数。它计算梯度，该梯度确定是否可以增加或减少权重以进一步减少损失函数。它还通过响应于函数的输出调整权重来链接模型参数和损失函数。
[返回](#85ae)

*训练数据*是一个数据集，用于机器学习以拟合模型参数，从而做出准确的预测。它包含全部数据集的大约 70–80 %,用于构建模型，并在多个训练周期中使用，以提高模型的准确性。它还可以包括用于监督学习的标签和注释。
[回车](#85ae)

*预测警务*是一种在机器学习中用于预测潜在未来犯罪的模型。它分析历史犯罪数据，以帮助决定在哪里部署警察，并识别更有可能实施犯罪或成为犯罪受害者的个人。这也引起了公民权利和公民自由对加强刑事司法系统中的种族偏见的关注。
[ [返回](#6549)

*正反馈循环*是机器学习中的一种情况，在这种情况下，预测产生的结果会加强相同的预测。它可以通过创建更多的数据来影响偏见，从而进一步扭曲这些偏见。它还可能影响决策系统，甚至可能以对历史上弱势群体更加不利的方式重塑人口。
[ [返回](#6549) ]

*随机抽样*是一种[抽样](#3edd)技术，用于机器学习中收集无偏样本。它包括从总体中选择观测值，使每个观测值都有均等的机会被选中。如果样本最终没有反映总体，它也会导致错误，因此它主要用于对总体了解甚少的情况。
[ [返回](#5e8d)

*采样*是机器学习中使用的一个过程，用于根据人口子集的结果预测人口的特性。它可以提高模型的准确性，减少构建模型所需的时间、成本和复杂性。如果样本不能代表总体，也会无意中降低模型的准确性。
[回车](#2647)

*输出层*是人工神经网络中用于进行预测的最后一层。它接收来自前几层的输入，通过其神经元执行计算，并计算输出。它还根据正在解决的问题类型(包括各种分类和回归问题)使用不同的激活函数。
[返回](#9b22)

## 附录:

![](img/3d48b2b5f694461b625f39f300a53c2d.png)

1.答:下载并安装快速 AI 库和依赖项。[ [Return](#dcb9)

![](img/bf4157feb6693e6b08653d0f7c273cca.png)

2.答:导入整个 Fast AI 库。[ [Return](#dcb9)

![](img/773f81c6786c41368b3e8acdaba26208.png)

3.答:下载数据集和预训练模型，并重新训练模型。[ [Return](#dcb9)

![](img/991adf019f1cf3345da1548b9b8f9f71.png)

4.答:打印方程式的结果。[ [返回](#dcb9)

![](img/79a402f0ba12c60d3339c24633670929.png)

5.答:加载并显示一只猫的图像。[ [返回](#dcb9)

![](img/58cddb666a05a06845e00ede0f361a4b.png)

6.答:显示一个小部件，可以选择要上传的图像。[ [返回](#dcb9)

![](img/543bf4a27a5d3ad2beec398ec66545cf.png)

7.答:用预定义的图像替换选定的图像。[ [返回](#dcb9)

![](img/7be55ea82aef387f87d435e595cdbd1e.png)

8.答:加载预定义的图像，进行预测，并打印结果。[ [返回](#dcb9)

![](img/5105a00d37139dde0dadc7b66c2b17a9.png)

9.答:下载数据集和预训练模型，并重新训练模型。【[归来](#dcb9)

![](img/a4db2629493dbd62a29b7a9eb2157324.png)

10.答:进行预测并显示结果。[ [返回](#dcb9)

![](img/792beb0b4c84dfa81f4c1495c1822205.png)

11.答:下载数据集和预训练模型，并重新训练模型。[ [返回](#dcb9)

![](img/c5759bdd6fb779dc09d26f91147ebf0b.png)

12.答:做一个预测。[ [Return](#dcb9)

![](img/8b9c448f1460f2a09dc69047d778ee50.png)

13.答:加载数据集，并指定列名和预处理步骤。[ [回车](#dcb9)

![](img/c786c7275f3fb831cd1fdae47d5ad799.png)

14.答:从头开始训练模型。[ [返回](#dcb9)

![](img/9af623b449b79d96545c76d194e217b3.png)

15.答:加载数据集，指定取值范围，重新训练模型。[ [回车](#dcb9)

![](img/353de0e33c4463134ecd7219dbb7c596.png)

16.答:进行预测并显示结果。[ [返回](#dcb9) ]