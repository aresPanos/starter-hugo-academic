---
title: "Decomposable Transformer Point Processes"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date). It has to be before current date if you want to sse it in your page (A).
publishDate: "2024-12-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *the 37th Conference on Neural Information Processing Systems (NeurIPS 2023)*
publication_short: In *the 37th Conference on Neural Information Processing Systems (NeurIPS 2023)*

abstract: The standard paradigm of modeling marked point processes is by parameterizing the intensity function using an attention-based (Transformer-style) architecture. Despite the flexibility of these methods, their inference is based on the computationally intensive thinning algorithm. In this work, we propose a framework where the advantages of the attention-based architecture are maintained and the limitation of the thinning algorithm is circumvented. The framework depends on modeling the conditional distribution of inter-event times with a mixture of log-normals satisfying a Markov property and the conditional probability mass function for the marks with a Transformer-based architecture. The proposed method attains state-of-the-art performance in predicting the next event of a sequence given its history. The experiments also reveal the efficacy of the methods that do not rely on the thinning algorithm during inference over the ones they do. Finally, we test our method on the challenging long-horizon prediction task and find that it outperforms a baseline developed specifically for tackling this task; importantly, inference requires just a fraction of time compared to the thinning-based baseline.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2409.18158'
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
