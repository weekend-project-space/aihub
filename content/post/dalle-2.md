---
title: "DallE-2"
description: "在过去的几年里，人工智能（AI）取得了极大的进展，而AI的新产品中有AI图像生成器。这是一种能够将输入的语句转换为图像的"
author: "瑞东"
date: "2023-03-31"
tags:
  - "AI模型"
  - "DallE-2"
  - "图像生成"
  - "艺术"
categories: AI绘画
series: "application"
website_link: "https://openai.com/dall-e-2/"
color: "#008DE1"

thumb_image: "/img/713c4fce5b943ad77a08c76688e26601.png"
cover_image: "/img/713c4fce5b943ad77a08c76688e26601.png"
---

在过去的几年里，人工智能（AI）取得了极大的进展，而AI的新产品中有AI图像生成器。这是一种能够将输入的语句转换为图像的工具。文本转图像的AI工具有许多，但最突出的就属DALL-E 2、Stable Diffusion和Midjourney了  DALL-E 2由OpenAI开发，它通过一段文本描述生成图像。其使用超过100亿个参数训练的GPT-3转化器模型，能够解释自然语言输入并生成相应的图像 DALL-E 2主要由两部分组成——将用户输入转换为图像的表示（称为Prior），然后是将这种表示转换为实际的照片（称为Decoder）  其中使用到的文本和图像嵌入来自另一个叫做CLIP（对比语言-图像预训练）的网络，这也是由OpenAI研发的。CLIP是一种神经网络，为输入的图像返回最佳的标题。它所做的事情与DALL-E 2所做的相反——它是将图像转换为文本，而DALL-E 2是将文本转换为图像。引入CLIP的目的是为了学习物体的视觉和文字表示之间的联系 ALL-E 2的工作是训练两个模型。第一个是Prior，接受文本标签并创建CLIP图像嵌入。第二个是Decoder，其接受CLIP图像嵌入并生成图像。模型训练完成之后，推理的流程如下： 输入的文本被转化为使用神经网络的CLIP文本嵌入 使用主成分分析（Principal Component Analysis）降低文本嵌入的维度 使用文本嵌入创建图像嵌入 进入Decoder步骤后，扩散模型被用来将图像嵌入转化为图像 图像被从64×64放大到256×256，最后使用卷积神经网络放大到1024×1024
