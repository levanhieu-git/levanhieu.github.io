---
title: "The TV is Smart and Full of Trackers: Measuring Smart TV Advertising and Tracking"
authors:
- Janus Varmarken
- Hieu Le
- Anastasia Shuba
- Athina Markopoulou
- Zubair Shafiq
date: "2020-05-08T00:00:00Z"
doi: "https://doi.org/10.2478/popets-2020-0021"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *In Proceedings of the Privacy Enhancing Technologies Symposium (PoPETs)*
publication_short: In *PoPETs*

abstract: In this paper, we present a large-scale measurement study of the smart TV advertising and tracking ecosystem. First, we illuminate the network behavior of smart TVs as used in the wild by analyzing network traffic collected from residential gateways. We find that smart TVs connect to well-known and platform-specific advertising and tracking services (ATSes). Second, we design and implement software tools that systematically explore and collect traffic from the top-1000 apps on two popular smart TV platforms, Roku and Amazon Fire TV. We discover that a subset of apps communicate with a large number of ATSes, and that some ATS organizations only appear on certain platforms, showing a possible segmentation of the smart TV ATS ecosystem across platforms. Third, we evaluate the (in)effectiveness of DNS-based blocklists in preventing smart TVs from accessing ATSes. We highlight that even smart TV-specific blocklists suffer from missed ads and incur functionality breakage. Finally, we examine our Roku and Fire TV datasets for exposure of personally identifiable information (PII) and find that hundreds of apps exfiltrate PII to third parties and platform domains. We also find evidence that some apps send the advertising ID alongside static PII values, effectively eliminating the user’s ability to opt out of ad personalization.

# Summary. An optional shortened abstract.
summary: In this paper, we present a large-scale measurement study of the smart TV advertising and tracking ecosystem. 

tags:
- Smart TV
- Ads & Tracking
- Network Measurement
featured: false

links:
- name: Firetastic Code
  url: https://github.com/UCI-Networking-Group/firetastic
- name: Rokustic Code
  url: https://github.com/UCI-Networking-Group/rokustic
url_pdf: https://content.sciendo.com/downloadpdf/journals/popets/2020/2/article-p129.xml
url_dataset: 'https://athinagroup.eng.uci.edu/projects/smarttv/data/'
url_project: 'https://athinagroup.eng.uci.edu/projects/smarttv/'
url_video: 'https://www.youtube.com/watch?v=E-Qt36TzD8s'

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

