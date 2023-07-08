# unet-pytorch
基于pytorch实现的unet图像语义分割算法（数据集天池地表建筑物识别）

* 框架:pytorch
* 网络结构:UNET
* 数据集:天池地表建筑物识别
* 数据集地址以及项目简介:https://tianchi.aliyun.com/competition/entrance/531872/information


# Unet图像分割算法
* 概述：图像处理语义分割算法，语义分割需要判断图像每个像素点的类别，进行精确分割。语义分割目前在自动驾驶、自动抠图、医疗影像等领域有着比较广泛的应用

* 网络结构：前半部分就是特征提取，后半部分是上采样（编码器-解码器结构）
* Encoder：左半部分，由两个3x3的卷积层（RELU）再加上一个2x2的maxpooling层组成一个下采样的模块（后面代码可以看出）；
* Decoder：有半部分，由一个上采样的卷积层（去卷积层）+特征拼接concat+两个3x3的卷积层（ReLU）反复构成（代码中可以看出来）；

先看博客吧

博客地址：https://blog.csdn.net/m0_47220500/article/details/121487582

# 零、项目获取
获取方式（点击下载）：[是云猿实战](https://shiyuncode.com/details?goodsCode=C00038)

项目经过多人测试运行，可以确保100%成功运行。

