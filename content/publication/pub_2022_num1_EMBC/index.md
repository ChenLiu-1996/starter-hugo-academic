---
title: "Segmentation with Residual Attention U-Net and an Edge-Enhancement Approach Preserves Cell Shape Features"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Nanyan Zhu
- admin
- Britney Forsyth
- Zakary S Singer
- Andrew F Laine
- Tal Danino
- Jia Guo

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2022-05-10T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference of the IEEE Engineering in Medicine & Biology Society (EMBC)*
publication_short: In *IEEE EMBC*

abstract: The ability to extrapolate gene expression dynamics in living single cells requires robust cell segmentation, and one of the challenges is the amorphous or irregularly shaped cell boundaries. To address this issue, we modified the U-Net architecture to segment cells in fluorescence widefield microscopy images and quantitatively evaluated its performance. We also proposed a novel loss function approach that emphasizes the segmentation accuracy on cell boundaries and encourages shape feature preservation. With a 97% sensitivity, 93% specificity, 91% Jaccard similarity, and 95% Dice coefficient, our proposed method called Residual Attention U-Net with edge-enhancement surpassed the state-of-the-art U-Net in segmentation performance as evaluated by the traditional metrics. More remarkably, the same proposed candidate also performed the best in terms of the preservation of valuable shape features, namely area, eccentricity, major axis length, solidity and orientation. These improvements on shape feature preservation can serve as useful assets for downstream cell tracking and quantification of changes in cell statistics or features over time.

# Summary. An optional shortened abstract.
summary: The addition of an edge-enhancement approach improved cell segmentation results over the baseline U-Net variant, in both traditional metrics and better preservation of cell shape features.


tags: ['conference']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: IEEE
  url: https://ieeexplore.ieee.org/document/9871026
- name: ArXiv
  url: https://arxiv.org/abs/2001.05548

url_pdf: 'https://arxiv.org/pdf/2001.05548.pdf'
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
          data-doi="10.1109/EMBC48229.2022.9871026"
          data-hide-zero-citations="false"
          data-legend="always">
        </span>
      <script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>
        <div  style="float:right";
          data-link-target="_blank"
          data-badge-details="right"
          data-badge-type="medium-donut"
          data-doi="10.1109/EMBC48229.2022.9871026"
          data-condensed="true"
          data-hide-no-mentions="false"
          class="altmetric-embed">
        </div>
    </div>
    <div id="inner">
      <script type="text/javascript" src="//cdn.plu.mx/widget-summary.js"></script>
        <a href="https://plu.mx/plum/a/?doi=10.1109/EMBC48229.2022.9871026"
          data-orientation="horizontal"
          class="plumx-summary"
          data-site="plum"
          data-hide-when-empty="false">
        </a>
    </div>
  </section>