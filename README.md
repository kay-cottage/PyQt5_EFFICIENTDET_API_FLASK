
# 基于Eifficientdet神经网络的AI医疗辅助识别系统


*注意：禁止用于商业用途，欢迎个人学习交流！*

## 描述

使用Opencv+Flask+Keras开发的基于Eifficientdet神经网络的细胞图像AI医疗辅助识别系统，采用PyQt5开发的简易GUI界面。
用户能够对细胞形态图象进行实时识别、分割，亦可以远程访问相关API接口进行目标检测；用户也可以更换.h5模型文件用来检测其他种类物体。


![Imgur](https://mmbiz.qpic.cn/mmbiz_png/QsUWqPChJWZVPxBOT3ibeZYYY2SJxXB1N7MTZQWvHg0l78EctmGS0auIESdEAuA2wbELAXpKLwGaXh9CTVTserw/0?wx_fmt=png)

## 环境


微软windows x64操作系统下运行


## 如何使用该软件?

您可以在windows x64的操作系统上直接从releases处下载该软件，解压或者安装直接点击使用


### 你需要了解什么 ?


#### 1. 项目由目录 model_data/，output/，outputcut/组成

* model_data：目录下存放模型文件，其中模型文件请统一命名为model.h5并放置在该目录下。(模型文件请在[efficientdet-d0-voc.h5](https://github.com/bubbliiiing/efficientdet-keras/releases/download/v1.0/efficientdet-d0-voc.h5) 即d0版本下迁移学习训练得到)

* 该目录下voc_classes.txt存放用以检测物体的种类信息，使用前请确认里面的信息是否正确，大部分报错原因都是因为模型与voc_classes.txt中的类别信息不匹配；

* output/：目录下存放检测后的图象，输入图象被检测后会将检测出的整张图象保存至该目录下

* outputcut/：该目录下存放检测并且分割后的图象

* 模型文件可以点击从这里下载（记得重命名为model.h5）：[efficientdet-d0-voc.h5](https://github.com/bubbliiiing/efficientdet-keras/releases/download/v1.0/efficientdet-d0-voc.h5)


* 更换模型后请记得重启程序


#### 2. 更多信息：

欢迎关注我的bilibili主页：https://space.bilibili.com/362186371

更多信息，相关视频会在那里更新

最后，该项目为个人想法的简单实现

不喜勿喷，谢谢哈
