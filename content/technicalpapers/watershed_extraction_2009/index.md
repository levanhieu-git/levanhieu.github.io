---
title: "Watershed Extraction"
authors:
- Hieu Le
date: "2009-03-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-03-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We devise an algorithm that extracts watersheds from digital elevation models. Flow direction is limited to one of the eight neighbors and only to a lower elevation. The algorithm runs in three stages to improve performance and lower memory usage. First it finds the edges within the flow network. It then finds the connected components. Finally, it creates a bitmap, which represents each watershed region with a different color. Performance is linearly proportional to the number of elevation values within a SRTM grid. The final bitmap reveals that the algorithm deals well with mountainous terrains but creates erroneous watershed regions for flat surfaces, forests, and lakes.

# Summary. An optional shortened abstract.
summary: In this paper, we devise an algorithm that extracts watersheds from digital elevation models. It creates a bitmap, which represents each watershed region with a different color. The final bitmap reveals that the algorithm deals well with mountainous terrains but creates erroneous watershed regions for flat surfaces, forests, and lakes.

tags:
- Watershed Extraction
featured: false

links:
url_pdf: https://drive.google.com/file/d/10GOOpJy7vdFVDp3KApr2FstalLZgIfRn/view?usp=sharing
url_code: https://github.com/MaxNanasy/river-networks
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

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
