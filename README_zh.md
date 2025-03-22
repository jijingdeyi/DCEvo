# DCEvo

Jinyuan Liu, Bowei Zhang, Qingyun Mei, Xingyuan Li, Yang Zou, Zhiying Jiang, Long Ma, Risheng Liu, Xin Fan, **"DCEvo: Discriminative Cross-dimensional Evolutionary Learning for Infrared and Visible Image Fusion"**,
IEEE/CVF Conference on Computer Vision and Pattern Recognition **(CVPR)**, 2025.

![Abstract](Figure/first_figure.jpg)


## 数据集
我们在 **"DCEvo/datasets"** 中提供了数据集的示例。

我们测试图像融合依据 [这个项目](https://github.com/RollingPlain/IVIF_ZOO/) 的完整数据集。


## 测试图像融合  
我们的模型参数被保存在 **"DCEvo/ckpt"**。 然后，可以通过以下代码测试我们的纯融合方法：
```
python test_Fusion.py
```


## 上色灰度图像
可以通过下方上色灰度图片用于任务引导的图像融合训练和测试：
```
python tocolor.py
```


## 测试任务人道的图像融合  
测试**"DCEvo/datasets/M3FD/images"** 中生成 **RGB 纯融合** 图像。
通过以下代码，可以测试任务引导的图像融合：
```
python test_task_guided_fusion.py
```


## 训练   
训练此过程需要先在**"DCEvo/datasets/M3FD/images"** 中生成 **RGB 纯融合** 图像。
通过以下代码，可以训练任务引导的图像融合：
```
python DCEvo_train.py
```
