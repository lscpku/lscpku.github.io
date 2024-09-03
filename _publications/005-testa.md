---
title: "TESTA: Temporal-Spatial Token Aggregation for Long-form Video-Language Understanding"
collection: publications
permalink: /publication/testa
excerpt: "Large-scale video-language pre-training has made remarkable strides in advancing video-language understanding tasks. However, the heavy computational burden of video encoding remains a formidable efficiency bottleneck, particularly for long-form videos. These videos contain massive visual tokens due to their inherent 3D properties and spatiotemporal redundancy, making it challenging to capture complex temporal and spatial relationships. To tackle this issue, we propose an efficient method called TEmporal-Spatial Token Aggregation (TESTA). TESTA condenses video semantics by adaptively aggregating similar frames, as well as similar patches within each frame. TESTA can reduce the number of visual tokens by 75% and thus accelerate video encoding. Building upon TESTA, we introduce a pre-trained video-language model equipped with a divided space-time token aggregation module in each video encoder block. We evaluate our model on five datasets for paragraph-to-video retrieval and long-form VideoQA tasks. Experimental results show that TESTA improves computing efficiency by 1.7 times, and achieves significant performance gains from its scalability in processing longer input frames, e.g., +13.7 R@1 on QuerYD and +6.5 R@1 on Condensed Movie."
venue: 'Findings of EMNLP 2023'
paperurl: 'https://arxiv.org/abs/2310.19060'
projecturl: 'https://github.com/RenShuhuai-Andy/TESTA'
authors: 'Shuhuai Ren, Sishuo Chen, <b>Shicheng Li</b>, Xu Sun, Lu Hou'
---
