---
title: "Assessing Neural Network Representations During Training Using Data Diffusion Spectra"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Danqi Liao
- admin
- Alexander Tong
- Guillaume Huguet
- Guy Wolf
- Maximilian Nickel
- Ian Adelstein
- Smita Krishnaswamy

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2023-06-18T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In 2023 ICML Workshop on Topology, Algebra, and Geometry in Machine Learning (TAG-ML)
publication_short: In *ICML 2023 TAG-ML Workshop*

abstract: Here we present information theoretic measures based on the data diffusion operator as characterisations of the representations learned by neural networks. Specifically, we define diffusion spectral entropy (DSE), i.e., entropy of the diffusion operator computed on the neural representation of a dataset as well as diffusion spectral mutual information (DSMI), which assesses the relationship between different sets of variables representing data. First, we show that these definitions form robust measures of intrinsic dimensionality and relationship strength respectively on toy data, outperforming binned Shannon entropy in terms of accuracy. Then we study the evolution of representations within classification networks and networks with self-supervised losses. In both cases, we see that generalizable training results in decrease in DSE over epochs --- starting from a random initialization. We also see that there is an increase in DSMI with the class label over time. On the other hand, training with corrupt labels results in a maintenance or increase in entropy and near-zero DSMI with labels. We also assess DSMI with the input and observe differing trends. On MNIST it grows until plateaus, whereas on CIFAR it increases and then decreases. Overall results show that these measures can elucidate characteristics of network performance as well as data complexity.

# Summary. An optional shortened abstract.
summary: We proposed an information-theory based framework to measure the entropy and mutual information of neural network representations.

tags: ['workshop']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: ICML Workshop
  url: https://openreview.net/pdf?id=DQW3ilre3Q
# - name: IEEE
#   url: https://ieeexplore.ieee.org/abstract/document/9433808/
# - name: Arxiv
#   url: https://arxiv.org/pdf/2104.04672.pdf

url_pdf: https://openreview.net/pdf?id=DQW3ilre3Q
url_code: https://github.com/ChenLiu-1996/DiffusionSpectralEntropy
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


<!-- <html>
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
          data-doi="10.3389/fnagi.2022.923673"
          data-hide-zero-citations="false"
          data-legend="always">
        </span>
      <script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>
        <div  style="float:right";
          data-link-target="_blank"
          data-badge-details="right"
          data-badge-type="medium-donut"
          data-doi="10.3389/fnagi.2022.923673"
          data-condensed="true"
          data-hide-no-mentions="false"
          class="altmetric-embed">
        </div>
    </div>
    <div id="inner">
      <script type="text/javascript" src="//cdn.plu.mx/widget-summary.js"></script>
        <a href="https://plu.mx/plum/a/?doi=10.3389/fnagi.2022.923673"
          data-orientation="horizontal"
          class="plumx-summary"
          data-site="plum"
          data-hide-when-empty="false">
        </a>
    </div>
  </section> -->