---
title: 'Bringing Textual Prompt to AI-Generated Image Quality Assessment'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 🌟Bowen Qu*
  - Haohui Li*
  - Wei Gao📧


date: '2024-02-22'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-22'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2024 IEEE International Conference on Multimedia and Expo (ICME)
publication_short: ICME2024

abstract: AI-Generated Images (AGIs) have inherent mul-timodal nature. Unlike traditional image quality assessment (IQA) on natural scenarios, AGIs quality assessment (AGIQA) takes the correspondence of image and its textual prompt into consideration. This is coupled in the ground truth score, which confuses the unimodal IQA methods. To solve this problem, we introduce IP-IQA (AGIs Quality Assessment via Image and Prompt), a multimodal framework for AGIQA via corresponding image and prompt incorporation. Specifically, we propose a novel incremental pretraining task named Image2Prompt for better understanding of AGIs and their corresponding textual prompts. An effective and efficient image-prompt fusion module, along with a novel special [QA] token, are also applied. Both are plug-and-play and beneficial for the cooperation of image and its corresponding prompt. Experiments demonstrate that our IP-IQA achieves the state-of-the-art on AGIQA-1k and AGIQA-3k datasets. Code will be available at https://github.com/Coobiw/IP-IQA.

# Summary. An optional shortened abstract.
summary: IP-IQA is the first multimodal model for AI-Generated Image Quality Assessment.

tags:
  - Multimodal Model for AI-Generated Image Quality Assessment

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2403.18714'
url_code: 'https://github.com/Coobiw/IP-IQA'
url_poster: 'https://github.com/Coobiw/IP-IQA/blob/master/assets/poster.pdf'

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

