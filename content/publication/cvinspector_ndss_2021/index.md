---
title: "CV-Inspector: Towards Automating Detection of Adblock Circumvention"
authors:
- Hieu Le
- Athina Markopoulou
- Zubair Shafiq
date: "2021-01-07T00:00:00Z"
#doi: "https://doi.org/10.2478/popets-2020-0021"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: accepted to the Network and Distributed System Security Symposium (NDSS 2021)
publication_short: accepted to *NDSS (2021)*

abstract: The adblocking arms race has escalated over the last few years. An entire new ecosystem of circumvention (CV) services has recently emerged that aims to bypass adblockers by obfuscating site content, making it difficult for adblocking filter lists to distinguish between ads and functional content. In this paper, we investigate recent anti-circumvention (anti-CV) efforts by the adblocking community that leverage custom filter lists. In particular, we analyze the anti-circumvention filter list (ACVL}, which supports advanced filter rules with enriched syntax and capabilities designed specifically to counter circumvention. We show that keeping ACVL rules up-to-date requires significant effort by expert list curators, who need to continuously monitor sites known to employ CV services and to discover new such sites in the wild; both tasks require considerable manual effort. To help automate and scale ACVL curation, we develop CV-Inspector, a machine learning approach for automatically detecting whether a site employs successful circumvention using differential execution analysis. We show that CV-Inspector achieves an F1-score 0.89 when detecting sites that successfully circumvent adblockers, and 0.94 for sites that do not. We apply CV-Inspector to discover sites that employ CV in the wild on top-20K sites. We also apply CV-Inspector to a list of sites that are known to utilize CV, and which are continuously monitored by ACVL authors, who counter CV by updating filter rules. In the latter case, we demonstrate that CV-Inspector reduces human labeling effort by 98%, which removes a major bottleneck for ACVL authors. Our work is the first large-scale study of the state of the circumvention arms race, and makes an important step towards automating anti-CV efforts.

# Summary. An optional shortened abstract.
summary: The adblocking arms race has escalated over the last few years. An entire new ecosystem of circumvention (CV) services has recently emerged that aims to bypass adblockers by obfuscating site content, making it difficult for adblocking filter lists to distinguish between ads and functional content. In this paper, we investigate recent anti-circumvention (anti-CV) efforts by the adblocking community that leverage custom filter lists. To help automate and scale ACVL curation, we develop CV-Inspector, a machine learning approach for automatically detecting whether a site employs successful circumvention using differential execution analysis.

tags:
- Anti-circumvention
- Ads & Tracking
- Web Measurement
featured: false

links:
- name: Short Talk
  url: https://levanhieu.com/talk/adblockerdevsummit_2020/
#- name: Rokustic Code
#  url: https://github.com/UCI-Networking-Group/rokustic
#url_pdf: https://content.sciendo.com/downloadpdf/journals/popets/2020/2/article-p129.xml
#url_dataset: 'https://athinagroup.eng.uci.edu/projects/smarttv/data/'
#url_project: 'https://athinagroup.eng.uci.edu/projects/smarttv/'
#url_video: 'https://www.youtube.com/watch?v=E-Qt36TzD8s'
#url_code: '#'
#url_poster: '#'
#url_slides: ''
#url_source: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

