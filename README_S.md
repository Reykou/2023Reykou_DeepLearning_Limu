# LimuDeepLearning

## 安装遇到的问题：

1. Pytorch

   [How to Install PyTorch GPU for Mac M1/M2 with Cond
   ](https://www.youtube.com/watch?v=VEDy-c5Sk8Y)**Mac M1** : conda env create -f torch-conda-nightly.yml -n torch
2. d2l 安装提示 numpy 有问题，但本地有 numpy

   查找说是 M1 芯片没有对应的 numpy0.7的版本？

   解决办法：把d2l 直接下载下来，放到 .ipynb 同级文件夹内，可运行！

## 上课中的问题

1. 查看文件目录 index.ipynb
2. [Pytorch API](https://pytorch.org/docs/stable/index.html)
3. 数据集 [fashion-mnist](https://github.com/zalandoresearch/fashion-mnist)

   [Machine Learning Meets Fashion](https://www.youtube.com/watch?v=RJudqel8DVA)
5. [Pytorch 数据集 API](https://pytorch.org/vision/stable/datasets.html)

   1. MNIST：手写数字图像数据集，用于数字识别任务。
   2. FashionMNIST：时尚商品图像数据集，用于图像分类任务。
   3. CIFAR-10和CIFAR-100：包含10类和100类物体图像的数据集，用于图像分类任务。
   4. ImageNet：大规模图像数据集，包含多个物体类别，用于图像分类和目标检测任务。
   5. COCO：包含各种物体类别的大型目标检测和分割数据集。
   6. VOC：视觉对象类别识别挑战赛（Visual Object Classes）数据集，用于目标检测和分割任务。
   7. Cityscapes：城市街景数据集，用于语义分割任务。
   8. SBD：标注了大量图像语义分割标签的数据集。
   9. CelebA：包含名人面部图像和相关注释的数据集，用于人脸识别和人脸属性分析任务。
   10. LSUN：大规模场景理解数据集，包含多个场景类别的图像。
   11. SVHN：街道数字图像数据集，用于数字识别任务。
