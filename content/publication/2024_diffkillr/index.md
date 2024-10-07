---
title: "DiffKillR: Killing and Recreating Diffeomorphisms for Cell Annotation in Dense Microscopy Images"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Danqi Liao
- Alejandro Parada-Mayorga
- Alejandro Ribeiro
- Marcello DiStasio
- Smita Krishnaswamy

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2024-09-10T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *ArXiv*
publication_short: In *ArXiv*

abstract: 'The proliferation of digital microscopy images, driven by advances in automated whole slide scanning, presents significant opportunities for biomedical research and clinical diagnostics. However, accurately annotating densely packed information in these images remains a major challenge. To address this, we introduce DiffKillR, a novel framework that reframes cell annotation as the combination of archetype matching and image registration tasks. DiffKillR employs two complementary neural networks: one that learns a diffeomorphism-invariant feature space for robust cell matching and another that computes the precise warping field between cells for annotation mapping. Using a small set of annotated archetypes, DiffKillR efficiently propagates annotations across large microscopy images, reducing the need for extensive manual labeling. More importantly, it is suitable for any type of pixel-level annotation. We will discuss the theoretical properties of DiffKillR and validate it on three microscopy tasks, demonstrating its advantages over existing supervised, semi-supervised, and unsupervised methods.'

# Summary. An optional shortened abstract.
summary: 'We transformed label-efficient annotation into the combination of archetype matching and image registration tasks. We proposed two complementary networks: one invariant and the other sensitive to diffeomorphisms.'

tags: ['preprint']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Arxiv
  url: https://arxiv.org/abs/2410.03058

url_pdf: https://arxiv.org/pdf/2410.03058
url_code: https://github.com/ChenLiu-1996/DiffKillR
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

<!--
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
          data-doi="10.48550/arXiv.2406.???"
          data-hide-zero-citations="false"
          data-legend="always">
        </span>
      <script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>
        <div  style="float:right";
          data-link-target="_blank"
          data-badge-details="right"
          data-badge-type="medium-donut"
          data-doi="10.48550/arXiv.2406.???"
          data-condensed="true"
          data-hide-no-mentions="false"
          class="altmetric-embed">
        </div>
    </div>
    <div id="inner">
      <script type="text/javascript" src="//cdn.plu.mx/widget-summary.js"></script>
        <a href="https://plu.mx/plum/a/?doi=10.48550/arXiv.2406.???"
          data-orientation="horizontal"
          class="plumx-summary"
          data-site="plum"
          data-hide-when-empty="false">
        </a>
    </div>
  </section> -->