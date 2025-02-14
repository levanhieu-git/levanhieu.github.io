---
title: "AutoFR: Automated Filter Rule Generation for Adblocking"
authors:
- Hieu Le
- Salma Elmalaki
- Athina Markopoulou
- Zubair Shafiq

date: "2025-02-01T00:00:00Z"
#doi: "https://doi.org/10.2478/popets-2020-0021"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ACM Transactions on Privacy and Security
publication_short: ACM Transactions on Privacy and Security

abstract: "Adblocking relies on filter lists, which are manually curated and maintained by a community of filter list authors. Filter list curation is a laborious process that does not scale well to a large number of sites or over time. In this article, we introduce AutoFR, a reinforcement learning framework to fully automate the process of filter rule creation and evaluation for sites of interest. We design an algorithm based on multi-arm bandits to generate filter rules that block ads while controlling the trade-off between blocking ads and avoiding visual breakage. We test AutoFR on thousands of sites and show that it is efficient: It takes only a few minutes to generate filter rules for a site of interest. AutoFR is effective: It optimizes filter rules for a particular site that can block 86% of the ads, as compared to 87% by EasyList, while achieving comparable visual breakage. Using AutoFR as a building block, we devise three methodologies that generate filter rules across sites based on: (1) a modified version of AutoFR, (2) rule popularity, and (3) site similarity. We conduct an in-depth comparative analysis of these approaches by considering their effectiveness, efficiency, and maintainability. We demonstrate that some of them can generalize well to new sites in both controlled and live settings. We envision that AutoFR can assist the adblocking community in automatically generating and updating filter rules at scale."

# Summary. An optional shortened abstract.
summary: 

tags:
- Filter rule generation
- Adblocking
featured: false

links:
#- name: Short Talk
#  url: https://levanhieu.com/talk/adblockerdevsummit_2020/
#- name: Rokustic Code
#  url: https://github.com/UCI-Networking-Group/rokustic
#- name: Extended Paper
#  url: https://arxiv.org/abs/2202.12872
#url_project: 'https://athinagroup.eng.uci.edu/projects/ats-on-the-web/'
url_pdf: https://dl.acm.org/doi/full/10.1145/3703836
#url_code: https://github.com/UCI-Networking-Group/AutoFR
#url_dataset: https://athinagroup.eng.uci.edu/projects/ats-on-the-web/autofr-dataset/
#url_video: 'https://www.youtube.com/watch?v=E-Qt36TzD8s'
#url_poster: '#'
#url_slides: ''
#url_source: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [arXiv](https://arxiv.org/abs/2106.05407)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

---

