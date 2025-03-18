# DCEvo

Jinyuan Liu, Bowei Zhang, Qingyun Mei, Xingyuan Li, Yang Zou, Zhiying Jiang, Long Ma, Risheng Liu, Xin Fan, **"DCEvo: Discriminative Cross-dimensional Evolutionary Learning for Infrared and Visible Image Fusion"**,
IEEE/CVF Conference on Computer Vision and Pattern Recognition **(CVPR)**, 2025.

![Abstract](Figure/first_figure.jpg)



## Datasets
We provide a demo dataset in **"DCEvo/datasets"**.

We test image fusion full datasets according to the [project](https://github.com/RollingPlain/IVIF_ZOO/).  




## Test Image Fusion  
Our checkpoints can be found in **"DCEvo/ckpt"**. Then, you can test our pure fusion method through
```
python test_Fusion.py
```


## Test Task-Guided Image Fusion  
You can test our task-guided fusion method through
```
python test_task_guided_fusion.py
```


## Train Task-Guided Image Fusion  
You can train our task-guided fusion method through
```
python DCEvo_train.py
```
