---
title: "Symmetry-Aware Actor-Critic for 3D Molecular Design"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- gsimm
- admin
- gcsanyi
- jmhlobato

date: "2021-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Learning Representations*
publication_short: In *ICLR*

abstract: Automating molecular design using deep reinforcement learning (RL) has the potential to greatly accelerate the search for novel materials. Despite recent progress on leveraging graph representations to design molecules, such methods are fundamentally limited by the lack of three-dimensional (3D) information. In light of this, we propose a novel actor-critic architecture for 3D molecular design that can generate molecular structures unattainable with previous approaches. This is achieved by exploiting the symmetries of the design process through a rotationally covariant state-action representation based on a spherical harmonics series expansion. We demonstrate the benefits of our approach on several 3D molecular design tasks, where we find that building in such symmetries significantly improves generalization and the quality of generated molecules.

# Summary. An optional shortened abstract.
summary: We propose an actor-critic architecture for 3D molecular design that exploits the symmetries of the design process using spherical harmonics.

tags: [reinforcement learning, molecular design, chemistry, covariant neural networks]

# Display this page in the Featured widget?
featured: true

links:
- name: PDF
  url: https://openreview.net/pdf?id=jEYKjPE1xYN
- name: Code
  url: https://github.com/gncs/molgym
- name: Blog
  url: https://mlg-blog.com/2021/04/30/reinforcement-learning-for-3d-molecular-design.html
- name: Preprint
  url: https://arxiv.org/abs/2011.12747
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
  focal_point: "Right"
  preview_only: false

---
