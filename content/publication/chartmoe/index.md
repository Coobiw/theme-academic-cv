---
title: 'ChartMoE: Mixture of Diversely Aligned Expert Connector for Chart Understanding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhengzuo Xu*
  - 🌟Bowen Qu*
  - Yiyan Qi*
  - Sinan Du
  - Chengjin Xu
  - Chun Yuan📧
  - Jian Guo📧

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - Author
  - Author
  - Author
  - Author

date: '2025-01-22'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-22'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2025 International Conference on Learning Representations (Oral Presentation, 1.8%)
publication_short: ICLR2025 Oral (1.8%)

abstract: Automatic chart understanding is crucial for content comprehension and document parsing. Multimodal Large Language Models (MLLMs) have demonstrated remarkable capabilities in chart understanding through domain-specific alignment and fine-tuning. However, current MLLMs still struggle to provide faithful data and reliable analysis only based on charts. To address it, we propose `ChartMoE`, which employs the Mixture of Expert (MoE) architecture to replace the traditional linear projector to bridge the modality gap. Specifically, we train several linear connectors through distinct alignment tasks, which are utilized as the foundational initialization parameters for different experts. Additionally, we introduce `ChartMoE-Align`, a dataset with nearly 1 million chart-table-JSON-code quadruples to conduct three alignment tasks (chart-table/JSON/code). Combined with the vanilla connector, we initialize different experts diversely and adopt highquality knowledge learning to further refine the MoE connector and LLM parameters. Extensive experiments demonstrate the effectiveness of the MoE connector and our initialization strategy, e.g., `ChartMoE` improves the accuracy of the previous state-of-the-art from 80.48% to 84.64% on the ChartQA benchmark.

# Summary. An optional shortened abstract.
summary: ChartMoE is a multimodal large language model with Mixture-of-Expert connector for advanced chart 1️⃣understanding, 2️⃣replot, 3️⃣editing, 4️⃣highlighting and 5️⃣transformation.

tags:
  - MoE in Downstream Tasks
  - MLLM
  - Chart Understanding

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2409.03277'
url_code: 'https://github.com/IDEA-FinAI/ChartMoE'
url_dataset: 'https://huggingface.co/datasets/Coobiw/ChartMoE-Data'
# url_poster: ''
# url_project: 'https://chartmoe.github.io/'
url_slides: 'https://zhuanlan.zhihu.com/p/31634026232'
url_source: 'https://mp.weixin.qq.com/s/9anQbcCahVLnXhNj7aU48Q'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false


---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

