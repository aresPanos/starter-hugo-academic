---
title: "Efficient Few-Shot Continual Learning in Vision-Language Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Rahaf Aljundi
- Daniel Olmeda Reino
- Richard E. Turner

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-05-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date). It has to be before current date if you want to sse it in your page (A).
publishDate: "2025-04-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Transactions on Machine Learning Research*
publication_short: In *Transactions on Machine Learning Research* 

abstract: Vision-language models (VLMs) excel at tasks like visual question answering and image captioning, but their reliance on frozen, pretrained image encoders like CLIP often leads to persistent vision errors that degrade downstream performance. Moreover, real-world deployment demands that VLMs continually adapt to new, scarce data in a few-shot setting without forgetting prior knowledge. To meet these challenges, we introduce LoRSU (Low-Rank Adaptation with Structured Updates), a lightweight and robust technique for few-shot continual learning of VLMs’ image encoders. Our approach leverages theoretical insights to identify and update only the most critical parameters, achieving significant resource efficiency. Specifically, we demonstrate that LoRSU reduces computational overhead by over 25x compared to full VLM updates, without sacrificing performance. In experiments on VQA benchmarks under a few-shot continual learning protocol, LoRSU demonstrates superior scalability, efficiency, and accuracy, offering a practical solution for dynamic, resource-constrained vision-language applications.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/forum?id=sQ1w92WW0V'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: False

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
