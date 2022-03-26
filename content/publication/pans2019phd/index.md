---
title: "Extreme multi-label learning with Gaussian processes"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-08-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date). It has to be before current date if you want to sse it in your page (A).
publishDate: "2019-08-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: In *Ph.D. thesis*
publication_short: In *Ph.D. thesis*

abstract: In modern probabilistic machine learning, Gaussian process models have provided both powerful and principled ways to approach a series of challenging problems. Nonetheless, their applicability can be significantly limited by cases where the number of training data points is large, something very typical in many modern machine learning applications. An additional restriction can be imposed when the posterior distribution is intractable due to non-Gaussian likelihoods used. Despite the fact that these two limitations have been efficiently addressed over the last decade, applications of Gaussian process models under extreme regimes where the number of the training data points and the dimensionality of both input and output space is extremely large have not appeared in literature so far. This thesis is focused on this kind of applications of Gaussian processes where supervised tasks such as multi-class and multi-label classification are considered. We start by discussing the main mathematical tools required in order to successfully cope with the large scale of the datasets. Those include a variational inference framework, suitably tailored for Gaussian processes. Furthermore, in our attempt to alleviate the computational burden, we introduce a new parametrization for the variational distribution while a representation trick for reducing storage requirements for large input dimensions is also discussed. A methodology is then presented which is based on this variational inference framework and a computationally efficient bound on the softmax function that allows the use of Gaussian processes for multi-class classification problems that involve arbitrarily large number of classes. A series of experiments test and compare the performance of this methodology with other methods. Finally, we move to the more general multi-label classification task and we develop a method, also relied on the same variational inference framework, which can deal with datasets involving hundreds of thousands data points, input dimensions and labels. The effectiveness of our method is supported by experiments on several real-world multi-label datasets.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://discovery.ucl.ac.uk/id/eprint/10087208/1/phd_thesis.pdf'
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

