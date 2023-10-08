 | 第二届计图挑战赛热身赛开源

# Jittor 计图挑战热身赛 baseline
| 标题名称包含赛题、方法

![主要结果](https://s3.bmp.ovh/imgs/2022/04/19/440f015864695c92.png)

｜展示方法的流程特点或者主要结果等

## 简介
| 简单介绍项目背景、项目特点

本项目包含了第三届计图挑战赛计图 - 热身赛的代码实现。本项目的特点是：采用了 Conditional generative adversarial nets 方法对 MNIST数据集进行训练处理，并生成特定数字的图像。

## 安装 
| 介绍基本的硬件需求、运行环境、依赖安装方法

本项目可在 1 张 3080 上运行,训练时间约为 6 小时。

#### 运行环境
- ubuntu 20.04.6 LTS
- python >= 3.7
- jittor

## 训练
｜ 介绍模型训练的方法

运行以下命令：
```
bash scripts/train.sh
```

多卡训练可以运行以下命令：
```
Python CGAN.py
```

## 推理
｜ 介绍模型推理、测试、或者评估的方法

生成测试集上的结果可以运行以下命令：

```
bash scripts/test.sh
```

## 致谢

此项目基于论文 *A Style-Based Generator Architecture for Generative Adversarial Networks* 实现，部分代码参考了 [jittor-jgan]([https://github.com/Jittor/gan-jittor](https://github.com/Jittor/JGAN))。

