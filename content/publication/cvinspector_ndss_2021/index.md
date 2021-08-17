---
title: "CV-Inspector: Towards Automating Detection of Adblock Circumvention"
authors:
- Hieu Le
- Athina Markopoulou
- Zubair Shafiq
date: "2020-12-04T00:00:00Z"
#doi: "https://doi.org/10.2478/popets-2020-0021"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Network and Distributed System Security Symposium (NDSS 2021)
publication_short: NDSS 2021

abstract: The adblocking arms race has escalated over the last few years. An entire new ecosystem of circumvention (CV) services has recently emerged that aims to bypass adblockers by obfuscating site content, making it difficult for adblocking filter lists to distinguish between ads and functional content. In this paper, we investigate recent anti-circumvention efforts by the adblocking community that leverage custom filter lists. In particular, we analyze the anti-circumvention filter list (ACVL), which supports advanced filter rules with enriched syntax and capabilities designed specifically to counter circumvention. We show that keeping ACVL rules up-to-date requires expert list curators to continuously monitor sites known to employ CV services and to discover new such sites in the wild — both tasks require considerable manual effort. To help automate and scale ACVL curation, we develop CV-INSPECTOR, a machine learning approach for automatically detecting adblock circumvention using differential execution analysis. We show that CV-INSPECTOR achieves 93% accuracy in detecting sites that successfully circumvent adblockers. We deploy CV-INSPECTOR on top-20K sites to discover the sites that employ circumvention in the wild.We further apply CV-INSPECTOR to a list of sites that are known to utilize circumvention and are closely monitored by ACVL authors. We demonstrate that CV-INSPECTOR reduces the human labeling effort by 98%, which removes a major bottleneck for ACVL authors. Our work is the first large-scale study of the state of the adblock circumvention arms race, and makes an important step towards automating anti-CV efforts.

# Summary. An optional shortened abstract.
summary: The adblocking arms race has escalated over the last few years. An entire new ecosystem of circumvention (CV) services has recently emerged that aims to bypass adblockers by obfuscating site content, making it difficult for adblocking filter lists to distinguish between ads and functional content. In this paper, we investigate recent anti-circumvention efforts by the adblocking community that leverage custom filter lists. In particular, we analyze the anti-circumvention filter list (ACVL), which supports advanced filter rules with enriched syntax and capabilities designed specifically to counter circumvention. To help automate and scale ACVL curation, we develop CV-INSPECTOR, a machine learning approach for automatically detecting adblock circumvention using differential execution analysis.

tags:
- Circumvention
- Adblocking
- Differential Analysis
featured: false

links:
#- name: Short Talk
#  url: https://levanhieu.com/talk/adblockerdevsummit_2020/
#- name: Rokustic Code
#  url: https://github.com/UCI-Networking-Group/rokustic
- name: Amazon Machine Image
  url: https://athinagroup.eng.uci.edu/projects/cv-inspector/ami/
- name: NDSS 2021 Video
  url: https://www.youtube.com/watch?v=tmNL_LYZVD0&list=PLfUWWM-POgQsqggYwKZDfhGRvIwvApfzz&index=2
url_project: 'https://athinagroup.eng.uci.edu/projects/cv-inspector/'
url_pdf: https://www.ndss-symposium.org/wp-content/uploads/2021-055b-paper.pdf
url_code: 'https://github.com/UCI-Networking-Group/cv-inspector'
url_dataset: 'https://athinagroup.eng.uci.edu/projects/cv-inspector/data/'
#url_video: 'https://www.youtube.com/watch?v=E-Qt36TzD8s'
#url_poster: '#'
#url_slides: ''
#url_source: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [Paper](https://www.ndss-symposium.org/wp-content/uploads/2021-055b-paper.pdf)'
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

