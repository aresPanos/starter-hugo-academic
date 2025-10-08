---
title: "Emergent Collusion and Backdoor Submissions in Multi-Agent LLM Code Reviews"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jennifer Za, admin, Roger Dearnaley, Samuel Albanie

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-12-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date). It has to be before current date if you want to sse it in your page (A).
publishDate: "2025-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *the 39th Conference on Neural Information Processing Systems (NeurIPS 2025), Workshop on Multi-Turn Interactions in Large Language Models*
publication_short: In *NeurIPS 2025, MTI-LLM Workshop*

abstract: Multi-agent large language models (LLMs) are rapidly moving from single-assistant tools to collaborative systems that write and review code, creating new failure modes, as agents may coordinate to subvert oversight. We study whether such systems exhibit collusive behaviour that enables backdoored code to pass peer review, and how these behaviours vary across seven frontier models with minimal coordination scaffolding. Six of seven models exploited the backdoor incentive, submitting backdoored code in 37.9–74.2% of attempts across 10 rounds, while GPT-5 largely refused (≤7.9%). Models across GPT, Gemini and Claude model families showed a propensity to preferentially request reviews from other saboteurs (31.9–38.8% vs 20% random), indicating selective coordination capabilities. Strikingly, GPT-4o-mini showed 27.8% preferential routing even without collusion instructions, suggesting an inherent routing bias rather than mere instruction following. Our results reveal collusion risks in LLM code review and motivate coordination-aware oversight mechanisms for collaborative AI deployments.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=CdZaamCf5Y'
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
