---
title: VLM4EO
summary: Vision Language Models for Earth Observation (VLM4EO)

draft: false
featured: false
tags:
  - Deep Learning


date: 2025-03-29T09:07:29.350Z
---

<div class=article-style itemprop=articleBody>

Foundation models have revolutionized artificial intelligence (AI), offering remarkable capabilities across multi-modal domains. Their ability to precisely locate objects in complex aerial and satellite images, using rich contextual information and detailed object descriptions, is essential for remote sensing (RS). These models can associate textual descriptions with object positions through the Visual Grounding (VG) task, but due to domain-specific challenges, their direct application to RS produces sub-optimal results. To address this, we applied Parameter Efficient Fine Tuning (PEFT) techniques to adapt these models for RS-specific VG tasks. Specifically, we evaluated LoRA placement across different modules in Grounding DINO and used BitFit and adapters to fine-tune the OFA foundation model pre-trained on general-purpose VG datasets. This approach achieved performance comparable to or surpassing current State Of The Art (SOTA) models while significantly reducing computational costs. This study highlights the potential of PEFT techniques to advance efficient and precise multi-modal analysis in RS, offering a practical and cost-effective alternative to full model training. 

</div>
