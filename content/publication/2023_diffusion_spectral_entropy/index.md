---
title: "Assessing Neural Network Representations During Training Using Noise-Resilient Diffusion Spectral Entropy"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Danqi Liao
- admin
- Ben Christensen
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
publication: In *International Conference on Machine Learning Workshop (ICMLW)*, and *IEEE Conference on Information Science and Systems (CISS)*
publication_short: In *ICML 2023 Workshop* and *CISS 2024*
publication_overlay: ICMLW 2023

abstract: Entropy and mutual information in neural networks provide rich information on the learning process, but they have proven difficult to compute reliably in high dimensions. Indeed, in noisy and high-dimensional data, traditional estimates in ambient dimensions approach a fixed entropy and are prohibitively hard to compute. To address these issues, we leverage data geometry to access the underlying manifold and reliably compute these information-theoretic measures. Specifically, we define diffusion spectral entropy (DSE) in neural representations of a dataset as well as diffusion spectral mutual information (DSMI) between different variables representing data. First, we show that they form noise-resistant measures of intrinsic dimensionality and relationship strength in high-dimensional simulated data that outperform classic Shannon entropy, nonparametric estimation, and mutual information neural estimation (MINE). We then study the evolution of representations in classification networks with supervised learning, self-supervision, or overfitting. We observe that (1) DSE of neural representations increases during training; (2) DSMI with the class label increases during generalizable learning but stays stagnant during overfitting; (3) DSMI with the input signal shows differing trends -- on MNIST it increases, while on CIFAR-10 and STL-10 it decreases. Finally, we show that DSE can be used to guide better network initialization and that DSMI can be used to predict downstream classification accuracy across 962 models on ImageNet.

# Summary. An optional shortened abstract.
summary: We propose a framework to measure the entropy and mutual information in high dimensions and is applicable to neural network representations.

tags: ['conference']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Arxiv
  url: https://arxiv.org/abs/2312.04823
- name: IEEE Information Theory Society
  url: https://ieeexplore.ieee.org/abstract/document/10480166
- name: Blog
  url: https://www.chenliu1996.com/publication/2024_explain_dse_dsmi/main.pdf

url_pdf: https://arxiv.org/pdf/2312.04823.pdf
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
          data-doi="10.1109/CISS59072.2024.10480166"
          data-hide-zero-citations="false"
          data-legend="always">
        </span>
      <script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>
        <div  style="float:right";
          data-link-target="_blank"
          data-badge-details="right"
          data-badge-type="medium-donut"
          data-doi="10.1109/CISS59072.2024.10480166"
          data-condensed="true"
          data-hide-no-mentions="false"
          class="altmetric-embed">
        </div>
    </div>
    <div id="inner">
      <script type="text/javascript" src="//cdn.plu.mx/widget-summary.js"></script>
        <a href="https://plu.mx/plum/a/?doi=10.1109/CISS59072.2024.10480166"
          data-orientation="horizontal"
          class="plumx-summary"
          data-site="plum"
          data-hide-when-empty="false">
        </a>
    </div>
  </section>