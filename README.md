# DeepLearning-IntroductionCourse
目前，很多深度学习教程都是从最基本的概念开始，结合大量的数学推导，逐步进行教学，最后才落实到具体的任务上。相比于这种Bottom-up的方法，fastai课程则强调Top-down的学习理念，我们直接从实际任务入手，通过编程快速实现世界领先的结果，可以先对深度学习有一个非常具象的认识，接着我们再逐渐深入这些结构，探寻它们背后的概念和方法。

在这门课程中，深度学习不再神秘，只需要你有一定的编程经验和一些基本的数学概念，fastai课程可以帮助你快速入门深度学习。fastai库是基于Pytorch实现的，同时做了很多优化，是一个非常强大同时速度极快的深度学习框架。

fastai库的GitHub链接如下：
https://github.com/fastai/fastai

课程主要分为两大部分，第一部分包含7个课时，介绍了如何利用深度学习去解决计算机视觉和自然语言处理领域的一些经典任务，同时对深度学习的一些重要概念和模型进行了详细阐述。第二部分同样包含7个课时，讲授了深度学习领域的一些前沿热点工作，介绍如何阅读这些论文并使用最新的技巧实现世界领先的结果。下面我们便简要介绍一下这14个课时的主要内容。

Lesson1 – Recognizing Cats and Dogs
这一课时主要介绍了环境配置、猫狗分类任务以及深度学习简介，我们将学到如何用短短几行代码实现领先的分类效果。

Lesson2 – Convolutional Neural Networks
这一课时详细介绍了在使用卷积神经网络（CNN）时常用的训练和测试流程，以及相应的技巧，并将此应用于几个实际的分类任务当中。

Lesson3 – Understanding Convolutions
这一课时主要介绍了Keras与fastai库的对比，通过一个实际的比赛讲授如何向Kaggle提交结果，最后对卷积神经网络进行了详细的阐述。

Lesson4 – Structured, Time Series, & Language Models
这一课时主要介绍了过拟合以及解决过拟合的有效方法—Dropout，同时以rossmann销量预测为例介绍了结构化时间序列模型，最后以IMDB影评情感判断为例对自然语言处理进行了初步地讲解。

Lesson5 – Collaborative Filtering; Inside the Training Loop
这一课时通过解决影评预测的任务介绍了协同过滤，特别是embedding的方法，并详细分析了随机梯度下降等在深度学习中经常使用的几种优化方法。

Lesson6 – RNNs From Scratch
这一课时主要对随机梯度下降法进行了代码实现，初步介绍了循环神经网络（RNN）的基本结构。

Lesson7 – ResNets From Scratch
这一课时通过建立语言模型，详细介绍了在自然语言处理任务中常用的几种RNN结构，同时在CIFAR-10数据集上逐步优化我们的CNN结构，并详细分析了BatchNrom和ResNet。

Lesson8 – Object Detection
这一课时详细介绍了目标检测任务，并通过代码实现了对图片中最大的目标进行检测。

Lesson9 – Single Shot Multibox Detector (SSD)
这一课时首先通过代码实现了SSD，取得了不错的目标检测效果，并详细分析了该领域最新的几篇论文，并通过实现它们提升了模型的效果。

Lesson10 – NLP Classification and Transfer Learing
这一课时通过之前完成过的影评情感判断任务，几乎是开创性地将迁移学习的方法引入这个自然语言处理任务当中，通过代码实现了世界领先的结果。

Lesson11 – Neural Translation; Multi-model learning
这一课时主要介绍了机器翻译模型，利用很多最新的技巧如注意力模型等实现了很好的效果，最后对视觉语义嵌入模型进行了简要的阐述和实现。

Lesson12 – DarkNet; Generative Adversarial Networks
这一课时主要分析了DarkNet的网络结构，接着对生成对抗网络（GAN）进行了介绍，并通过代码实现了WGAN模型和Cycle-GAN模型。

Lesson13 – Image Enhancement
这一课时主要介绍了fastai库的一些改进以及Inception Network，接着对图片风格迁移进行了详细介绍，并通过代码实现了初步的风格迁移。

Lesson14 – Super Resolution; Segmentation with Unets
这一课时详细介绍并实现了图像超分辨率的模型，并将其思想应用于风格迁移，从而优化了上一节课使用的方法，最后通过详细分析并实现Unet模型解决了Carvana这个图像分割任务。

资料包含了所有14个课时的课件和实现代码（代码均取自fastai课程）以及原版视频课程网站:

1-7课：http://course.fast.ai/lessons/lessons.html

8-14课：http://course.fast.ai/lessons/lessons2.html