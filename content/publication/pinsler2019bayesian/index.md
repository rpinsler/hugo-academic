---
title: "Bayesian Batch Active Learning as Sparse Subset Approximation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- jgordon
- enalisnick
- jmhlobato

date: "2019-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-08-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Advances in Neural Information Processing Systems*
publication_short: In *NeurIPS*

abstract: Leveraging the wealth of unlabeled data produced in recent years provides great potential for improving supervised models. When the cost of acquiring labels is high, probabilistic active learning methods can be used to greedily select the most informative data points to be labeled. However, for many large-scale problems standard greedy procedures become computationally infeasible and suffer from negligible model change. In this paper, we introduce a novel Bayesian batch active learning approach that mitigates these issues. Our approach is motivated by approximating the complete data posterior of the model parameters. While naive batch construction methods result in correlated queries, our algorithm produces diverse batches that enable efficient active learning at scale. We derive interpretable closed-form solutions akin to existing active learning procedures for linear models, and generalize to arbitrary models using random projections. We demonstrate the benefits of our approach on several large-scale regression and classification tasks. 

# Summary. An optional shortened abstract.
summary: We propose a novel Bayesian batch active learning approach motivated by approximating the complete data posterior of the model parameters.

tags: [active learning, bayesian deep learning, approximate inference]

# Display this page in the Featured widget?
featured: true

links:
- name: PDF
  url: https://papers.nips.cc/paper/2019/file/84c2d4860a0fc27bcf854c444fb8b400-Paper.pdf
- name: Preprint
  url: https://arxiv.org/abs/1908.02144
- name: Code
  url: https://github.com/rpinsler/active-bayesian-coresets
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
  focal_point: ""
  preview_only: false

---
