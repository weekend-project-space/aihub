---
title: "Deepfloyd-新的开源图生文模型"
description: "Github：https://github.com/deep-floyd/IF 推特官网：https://twitter"
author: "瑞东"
date: "2023-03-30"
tags:
  - "AI绘画"
categories: AI绘画
series: "application"
website_link: "https://github.com/deep-floyd/IF"
color: "#008DE1"

thumb_image: "/img/fd2a38fc0632ae6dc0f3ebe7f915e38d.png"
cover_image: "/img/fd2a38fc0632ae6dc0f3ebe7f915e38d.png"
---

Github：https://github.com/deep-floyd/IF 推特官网：https://twitter.com/deepfloydai 这是一种新颖的最先进的开源文本到图像模型，具有高度的照片级真实感和语言理解。DeepFloyd IF 是一个由冻结文本编码器和三个级联像素扩散模块组成的模块：一个基于文本提示生成 64×64 像素图像的基本模型和两个超分辨率模型，每个模型都旨在生成分辨率不断提高的图像：256×256 像素和 1024×1024 像素。 该模型的所有阶段都利用基于 T5 转换器的冻结文本编码器来提取文本嵌入，然后将其馈送到通过交叉注意力和注意力池增强的 UNet 架构中。结果是一个高效的模型，优于当前最先进的模型，在COCO数据集上实现了6.66的零镜头FID分数  