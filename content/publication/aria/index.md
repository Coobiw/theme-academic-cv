---
title: "Aria: An Open Multimodal Native Mixture-of-Experts Model"
authors:
- Dongxu Li
- Yudong Liu 
- Haoning Wu
- Yue Wang 
- Zhiqi Shen 
- 🌟Bowen Qu
- Xinyao Niu 
- Fan Zhou
- Chengen Huang
- Yanpeng Li
- Chongyan Zhu
- Xiaoyi Ren
- Chao Li
- Yifan Ye
- Peng Liu
- Lihuan Zhang
- Hanshu Yan
- Guoyin Wang 
- Bei Chen 
- Junnan Li📧

date: "2024-10-05"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-05"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "Technical Report"
publication_short: "Technical Report"

abstract: Information comes in diverse modalities. Multimodal native AI models are essential to integrate real-world information and deliver comprehensive understanding. While proprietary multimodal native models exist, their lack of openness imposes obstacles for adoptions, let alone adaptations. To fill this gap, we introduce ARIA, an open multimodal native model with best-in-class performance across a wide range of multimodal, language, and coding tasks. ARIA is a mixture-of-expert model with 3.9B and 3.5B activated parameters per visual token and text token, respectively. It outperforms Pixtral-12B and Llama3.2-11B, and is competitive against the best proprietary models on various multimodal tasks. We pre-train ARIA from scratch following a 4-stage pipeline, which progressively equips the model with strong capabilities in language understanding, multimodal understanding, long context window, and instruction following. We open-source the model weights along with a codebase that facilitates easy adoptions and adaptations of ARIA in real-world applications.

# Summary. An optional shortened abstract.
summary: Aria is a multimodal native MoE model. It features：1️⃣State-of-the-art performance on various multimodal and language tasks, superior in video and document understanding; 2️⃣Long multimodal context window of 64K tokens; 3️⃣3.9B activated parameters per token, enabling fast inference speed and low fine-tuning cost.

tags:
- Multimodal Native MoE
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2410.05993
url_code: 'https://github.com/rhymes-ai/Aria'
url_dataset: 'https://huggingface.co/rhymes-ai/Aria'
# url_poster: ''
# url_project: ''
url_slides: 'https://rhymes.ai/blog-details/aria-first-open-multimodal-native-moe-model'
url_source: 'https://rhymes.ai/blog-details/aria-first-open-multimodal-native-moe-model'
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

