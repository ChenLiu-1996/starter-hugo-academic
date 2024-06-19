---
title: "CUTS: A Deep Learning and Topological Framework for Multigranular Unsupervised Medical Image Segmentation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Matthew Amodio
- Liangbo L. Shen
- Feng Gao
- Arman Avesta
- Sanjay Aneja
- Jay Wang
- Lucian V. Del Priore
- Smita Krishnaswamy

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2024-06-17T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In International Conference on Medical Image Computing and Computer-Assisted Intervention
publication_short: In MICCAI 2024

abstract: Segmenting medical images is critical to facilitating both patient diagnoses and quantitative research. A major limiting factor is the lack of labeled data, as obtaining expert annotations for each new set of imaging data and task can be labor intensive and inconsistent among annotators. We present CUTS, an unsupervised deep learning framework for medical image segmentation. CUTS operates in two stages. For each image, it produces an embedding map via intra-image contrastive learning and local patch reconstruction. Then, these embeddings are partitioned at dynamic granularity levels that correspond to the data topology. CUTS yields a series of coarse-to-fine-grained segmentations that highlight features at various granularities. We applied CUTS to retinal fundus images and two types of brain MRI images to delineate structures and patterns at different scales. When evaluated against predefined anatomical masks, CUTS improved the dice coefficient and Hausdorff distance by at least 10% compared to existing unsupervised methods. Further, CUTS shows performance on par with the Segment Anything Model which was pre-trained on 11 million images and 1.1 billion masks.

# Summary. An optional shortened abstract.
summary: An unsupervised framework for multiscale medical image segmentation, leveraging intra-image contrastive learning, patch-level reconstruction and diffusion condensation.

tags: ['conference']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: https://arxiv.org/abs/2209.11359

url_pdf: https://arxiv.org/pdf/2209.11359.pdf
url_code: https://github.com/ChenLiu-1996/CUTS
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption:
  focal_point: ""
  preview_only: false

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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

<html>
  <style>
    section {
        background: white;
        color: black;
        border-radius: 1em;
        padding: 1em;
        left: 50% }
    #inner {
        display: inline-block;
        display: flex;
        align-items: center;
        justify-content: center }
  </style>
  <section>
    <div id="inner">
      <script type='text/javascript' src='https://d1bxh8uas1mnw7.cloudfront.net/assets/embed.js'></script>
        <span style="float:left";
          class="__dimensions_badge_embed__"
          data-doi="10.48550/arXiv.2209.11359"
          data-hide-zero-citations="false"
          data-legend="always">
        </span>
      <script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>
        <div  style="float:right";
          data-link-target="_blank"
          data-badge-details="right"
          data-badge-type="medium-donut"
          data-doi="10.48550/arXiv.2209.11359"
          data-condensed="true"
          data-hide-no-mentions="false"
          class="altmetric-embed">
        </div>
    </div>
    <div id="inner">
      <script type="text/javascript" src="//cdn.plu.mx/widget-summary.js"></script>
        <a href="https://plu.mx/plum/a/?doi=10.48550/arXiv.2209.11359"
          data-orientation="horizontal"
          class="plumx-summary"
          data-site="plum"
          data-hide-when-empty="false">
        </a>
    </div>
  </section>