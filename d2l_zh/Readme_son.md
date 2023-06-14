安装遇到的问题：

1. Pytorch

   [How to Install PyTorch GPU for Mac M1/M2 with Cond
   ](https://www.youtube.com/watch?v=VEDy-c5Sk8Y)**Mac M1** : conda env create -f torch-conda-nightly.yml -n torch
2. d2l 安装提示 numpy 有问题，但本地有 numpy

   查找说是 M1 芯片没有对应的 numpy0.7的版本？

   解决办法：把d2l 直接下载下来，放到 .ipynb 同级文件夹内，可运行！
