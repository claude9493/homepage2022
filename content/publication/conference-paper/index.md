---
title: "Hop-Mix-DNS: Hop-wise Mixing Dynamic Negative Sampling for Graph
  Neural Network-based Recommendation Systems"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Shi Kexin
  - Jing Bingyi

# Author notes (optional)
author_notes:
  - 'yzhangjy@connect.ust.hk'
  - 'kshiaf@connect.ust.hk'
  - 'majing@ust.hk'

date: '2022-10-14T14:42:55.782Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Submitted
publication_short: 

abstract: "Recommendation system models users’ preference on items based on past
  interactions history. Lately, the graph neural network (GNN) has become a
  powerful collaborative filtering (CF) solution, which leverages the high-order
  connectivity information in the user-item bipartite graph. In training the
  GNN-based CF models, negative sampling plays an essential role in boosting the
  model’s performance and improving the training efficiency. However, there has
  been very limited literature on negative sampling for GNN-based CF. In this
  paper, we propose the Hop-Mix-DNS method, a novel negative sampling strategy
  for GNN-based recommenders. It first picks multiple hard negatives on each GNN
  layer then aggregates them with carefully designed coefficients to synthesize
  one ''virtual'' negative item. The advantages are twofold: 1) the model is
  trained more efficiently as several hard items are included in negative
  sampling so that there is a larger gradient, 2) it helps to improve the
  performance because the level of difficulty among negative items is more
  balanced for training the model. Empirical results on three real-world
  datasets demonstrate that the Hop-Mix-DNS consistently improves the
  state-of-the-art GNN-based CF model, LightGCN, by 27% in terms of NDCG@20.
  Training time is reduced by up to 60% compared to state-of-the-art negative
  sampling method."

# Summary. An optional shortened abstract.
summary: 

tags: ['GNN', 'Recommendation System']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: 'Overview of Hop-Mix-DNS'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
