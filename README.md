# Deep-Learning

---

## Computer Vision
1. LeNet

    - 提出者：Yann LeCun 等

    - 年份：1998

    - 任务：手写数字识别（MNIST）

    - 特点：第一个成功应用于实际任务的卷积神经网络，奠定了卷积神经网络的基础。

2. AlexNet

    - 提出者：Alex Krizhevsky, Ilya Sutskever, Geoffrey Hinton

    - 年份：2012

    - 任务：ImageNet 大规模视觉识别挑战赛（ILSVRC）

    - 特点：首次在大规模图像分类任务中使用深度卷积神经网络，显著提高了分类精度，开启了深度学习在计算机视觉领域的热潮。

3. VGG

    - 提出者：Karen Simonyan, Andrew Zisserman

    - 年份：2014

    - 任务：ImageNet 大规模视觉识别挑战赛（ILSVRC）

    - 特点：使用更小的卷积核（3x3）和更深的网络结构（16-19层），展示了深度对模型性能的重要性。

4. NIN (Network in Network)
    - 提出者：Min Lin, Qiang Chen, Shuicheng Yan

    - 年份：2013

    - 任务：图像分类

    - 特点：

    引入了 1x1 卷积层（点卷积），增强了特征的抽象能力。

    使用全局平均池化（Global Average Pooling）替代全连接层，减少参数数量，防止过拟合。

    提出了多层感知机卷积层（MLPConv），通过多层 1x1 卷积层增强特征的非线性表达能力。

5. GoogLeNet (Inception)

    - 提出者：Christian Szegedy 等

    - 年份：2014

    - 任务：ImageNet 大规模视觉识别挑战赛（ILSVRC）

    - 特点：引入了 Inception 模块，通过多尺度卷积核并行处理，减少了参数数量，提高了计算效率。

6. ResNet

    - 提出者：Kaiming He 等

    - 年份：2015

    - 任务：ImageNet 大规模视觉识别挑战赛（ILSVRC）

    - 特点：引入了残差连接（Residual Connection），解决了深度网络中的梯度消失问题，使得训练更深的网络成为可能。

7. DenseNet

    - 提出者：Gao Huang 等

    - 年份：2016

    - 任务：ImageNet 大规模视觉识别挑战赛（ILSVRC）

    - 特点：通过密集连接（Dense Connection），每一层都直接连接到所有后续层，增强了特征的复用，减少了参数数量。 