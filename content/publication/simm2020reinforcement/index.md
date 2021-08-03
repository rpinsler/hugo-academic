---
title: "Reinforcement Learning for Molecular Design Guided by Quantum Mechanics"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- gsimm
- admin
- jmhlobato

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Machine Learning*
publication_short: In *ICML*

abstract: Automating molecular design using deep reinforcement learning (RL) holds the promise of accelerating the discovery of new chemical compounds. Existing approaches work with molecular graphs and thus ignore the location of atoms in space, which restricts them to 1) generating single organic molecules and 2) heuristic reward functions. To address this, we present a novel RL formulation for molecular design in Cartesian coordinates, thereby extending the class of molecules that can be built. Our reward function is directly based on fundamental physical properties such as the energy, which we approximate via fast quantum-chemical methods. To enable progress towards de-novo molecular design, we introduce MolGym, an RL environment comprising several challenging molecular design tasks along with baselines. In our experiments, we show that our agent can efficiently learn to solve these tasks from scratch by working in a translation and rotation invariant state-action space.

# Summary. An optional shortened abstract.
summary: We present a reinforcement learning formulation that enables molecular design directly in Cartesian coordinates.

tags: [reinforcement learning, molecular design, chemistry]

# Display this page in the Featured widget?
featured: true

links:
- name: PDF
  url: https://proceedings.icml.cc/static/paper_files/icml/2020/1323-Paper.pdf
- name: Code
  url: https://github.com/gncs/molgym
- name: Blog
  url: https://mlg-blog.com/2021/04/30/reinforcement-learning-for-3d-molecular-design.html
- name: Preprint
  url: https://arxiv.org/abs/2002.07717
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
