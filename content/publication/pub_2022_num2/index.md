---
title: "Deep Learning of MRI Contrast Enhancement for Mapping Cerebral Blood Volume from Single-Modal Non-Contrast Scans of Aging and Alzheimer's Disease Brains"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Nanyan Zhu
- Haoran Sun
- Junhao Zhang
- Xinyang Feng
- Sabrina Gjerswold-Selleck
- Dipika Sikka
- Xuemin Zhu
- Xueqing Liu
- Tal Nuriel
- Hong-Jian Wei
- Cheng-Chia Wu
- Thomas J Vaughan
- Andrew F Laine
- Frank A Provenzano
- Scott A Small
- Jia Guo

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2022-07-16T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Frontiers in Aging Neuroscience*
publication_short: In *Frontiers in Aging Neuroscience*

abstract: While MRI contrast agents such as those based on Gadolinium are needed for high-resolution mapping of brain metabolism, these contrast agents require intravenous administration, and there are rising concerns over their safety and invasiveness. Furthermore, non-contrast MRI scans are more commonly performed than those with contrast agents and are readily available for analysis in public databases such as the Alzheimer's Disease Neuroimaging Initiative (ADNI). In this paper, we hypothesize that a deep learning model, trained using quantitative steady-state contrast-enhanced structural MRI datasets, in mice and humans, can generate contrast-equivalent information from a single non-contrast MRI scan. The model was first trained, optimized, and validated in mice, and was then transferred and adapted to humans. We observe that the model can substitute for Gadolinium-based contrast agents in approximating cerebral blood volume, a quantitative representation of brain activity, at sub-millimeter granularity. Furthermore, we validate the use of our deep-learned prediction maps to identify functional abnormalities in the aging brain using locally obtained MRI scans, and in the brain of Alzheimer's disease patients using publicly available MRI scans from ADNI. Since it is derived from a commonly-acquired MRI protocol, this framework has the potential for broad clinical utility and can also be applied retrospectively to research scans across a host of neurological/functional diseases.

# Summary. An optional shortened abstract.
summary: We developed and optimized a deep learning algorithm to produce Gadolinium contrast in mouse and human brain MRI directly from a single non-contrast structural MRI. We showed sensible prediction results by quantitatively comparing not only the contrast images but also the downstream scientific findings with the ground truths on two species, multiple studies, and various levels of brain disorders.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Published Online (Free Download)
  url: https://www.frontiersin.org/articles/10.3389/fnagi.2022.923673/abstract

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
  </section>