---
title: "TechCrunch Summary"
description: "带有 GPT-3 的新闻摘要器 – 专门用于 TechCrunch 文章。 该项目使用OpenAI GPT-3 API（"
author: "瑞东"
date: "2023-03-30"
tags:
  - "GPT"
  - "TechCrunch"
categories: 智能总结
series: "application"
website_link: "https://www.techcrunchsummary.com/"
color: "#666"

thumb_image: "/img/70f35879dd76f57974610071430bae26.png"
cover_image: "/img/70f35879dd76f57974610071430bae26.png"
---

带有 GPT-3 的新闻摘要器 – 专门用于 TechCrunch 文章。 该项目使用OpenAI GPT-3 API（特别是text-davinci-003）和Vercel Edge函数与流媒体。它获取 Techcrunch 文章中的内容，在提示中将其发送到 GPT-3 API 以通过 Vercel Edge 函数对其进行汇总，然后将响应流式传输回应用程序。