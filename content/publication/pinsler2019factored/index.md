---
title: "Factored Contextual Policy Search with Bayesian Optimization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- pkarkus
- akupcsik
- dhsu
- wslee

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2019-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-04-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Robotics and Automation*
publication_short: In *ICRA*

abstract: 'Scarce data is a major challenge to scaling robot learning to truly complex tasks, as we need to generalize locally learned policies over different task contexts. Contextual policy search offers data-efficient learning and generalization by explicitly conditioning the policy on a parametric context space. In this paper, we further structure the contextual policy representation. We propose to factor contexts into two components: target contexts that describe the task objectives, e.g. target position for throwing a ball; and environment contexts that characterize the environment, e.g. initial position or mass of the ball. Our key observation is that experience can be directly generalized over target contexts. We show that this can be easily exploited in contextual policy search algorithms. In particular, we apply factorization to a Bayesian optimization approach to contextual policy search both in sampling-based and active learning settings. Our simulation results show faster learning and better generalization in various robotic domains. See our supplementary video: https://youtu.be/IIJTbBAOufDY.'

# Summary. An optional shortened abstract.
summary: We factor contexts for contextual policy search into environment and target components, such that experience can be directly generalized over target contexts.

tags: [reinforcement learning, contextual policy search, bayesian optimization, robotics]

# Display this page in the Featured widget?
featured: false

links:
- name: Preprint
  url: https://arxiv.org/abs/1904.11761
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8793808'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/MNTbBAOufDY'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: ""
  preview_only: false

---
