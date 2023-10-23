---
title: "CUTS: A Framework for Multigranular Unsupervised Medical Image Segmentation"

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

date: "2023-02-18T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *ArXiv*
publication_short: In *ArXiv*

abstract: In this work we introduce CUTS (Contrastive and Unsupervised Training for Segmentation), the first fully unsupervised deep learning framework for medical image segmentation to better utilize the vast majority of imaging data that is not labeled or annotated. Segmenting medical images is a critical task for facilitating both patient diagnoses and quantitative research. A major limiting factor is the lack of labeled data, as obtaining expert annotations for each new set of imaging data or task can be expensive, labor intensive, and inconsistent across annotators. Thus, we utilize self-supervision from pixels and their local neighborhoods in the images themselves. Our unsupervised approach optimizes a training objective that leverages concepts from contrastive learning and autoencoding. In contrast to prior work, our framework segments medical images with a novel two-stage approach without relying on any labeled data at any stage. The first stage involves the creation of a "pixel-centered patch" that embeds every pixel along with its surrounding patch, using a vector representation in a high-dimensional latent embedding space. The second stage utilizes diffusion condensation, a multi-scale topological data analysis approach, to dynamically coarse-grain these embedding vectors at all levels of granularity. The final outcome is a series of coarse-to-fine segmentations that highlight image structures at various scales. We show successful multi-scale segmentation on natural images, retinal fundus images, and brain MRI images. Our framework delineates structures and patterns at different scales which may carry distinct information relevant to clinical interpretation. As we tackle the problem of segmenting medical images at multiple meaningful granularities without relying on any label, we demonstrate the possibility to circumvent tedious and repetitive manual annotations in future practice.

# Summary. An optional shortened abstract.
summary: We developed a fully unsupervised framework for image segmentation and investigated its performance on natural images and more importantly, two medical image datasets. The proposed framework combines intra-image contrastive learning and local patch reconstruction to jointly learn a structured latent space. Then, it coarse-grains the latent pixel-level embeddings into a series of coarse-to-fine segmentations at various levels of granularity. The proposed method is end-to-end unsupervised and outperforms existing unsupervised segmentation methods in our quantitative experiments.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: https://arxiv.org/abs/2209.11359

url_pdf: https://arxiv.org/pdf/2209.11359.pdf
url_code: https://github.com/ChenLiu-1996/UnsupervisedMedicalSeg
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