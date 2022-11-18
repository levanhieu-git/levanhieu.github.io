---
title: "OVRSeen: Auditing Network Traffic and Privacy Policies in Oculus VR"
authors:
- Rahmadi Trimananda
- Hieu Le
- Hao Cui
- Janice Ho
- Anastasia Shuba
- Athina Markopoulou
date: "2021-10-03T00:00:00Z"
#doi: "https://doi.org/10.2478/popets-2020-0021"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: USENIX Conference on Security Symposium (SEC) 2022
publication_short: USENIX Conference on Security Symposium (SEC) 2022

abstract: Virtual reality (VR) is an emerging technology that enables new applications but also introduces privacy risks. In this paper, we focus on Oculus VR (OVR), the leading platform in the VR space, and we provide the first comprehensive analysis of personal data exposed by OVR apps and the platform itself, from a combined networking and privacy policy perspective.We experimented with the Quest 2 headset, and we tested the most popular VR apps available on the official Oculus and the SideQuest app stores. We developed OVRSeen, a methodology and system for collecting, analyzing, and com-paring network traffic and privacy policies on OVR. On the networking side, we captured and decrypted network traffic ofVR apps, which was previously not possible on OVR, and we extracted data flows (defined as〈app, data type, destination〉).We found that the OVR ecosystem (compared to the mobile and other app ecosystems) is more centralized, and driven by tracking and analytics, rather than by third-party advertising.We show that the data types exposed by VR apps include personally identifiable information (PII), device information that can be used for fingerprinting, and VR-specific data types.By comparing the data flows found in the network traffic with statements made in the apps’ privacy policies, we discovered that approximately 70% of OVR data flows were not properly disclosed. Furthermore, we provided additional context for these data flows, including the purpose, which we extracted from the privacy policies, and observed that 69% were sent for purposes unrelated to the core functionality of apps.

# Summary. An optional shortened abstract.
summary: 

tags:
- Virtual Reality
- Oculus
- Network Traffic and Privacy Policy Consistency Analysis
featured: false

links:
#- name: Short Talk
#  url: https://levanhieu.com/talk/adblockerdevsummit_2020/
#- name: Rokustic Code
#  url: https://github.com/UCI-Networking-Group/rokustic
- name: arXiv
  url: https://arxiv.org/abs/2106.05407
url_project: 'https://athinagroup.eng.uci.edu/projects/ovrseen/'
url_pdf: https://arxiv.org/abs/2106.05407
# url_code: 'https://github.com/UCI-Networking-Group/cv-inspector'
# url_dataset: 'https://athinagroup.eng.uci.edu/projects/cv-inspector/data/'
#url_video: 'https://www.youtube.com/watch?v=E-Qt36TzD8s'
#url_poster: '#'
#url_slides: ''
#url_source: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [arXiv](https://arxiv.org/abs/2106.05407)'
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

