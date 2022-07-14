---
title: "Understanding and Modeling Climate Impacts on Photosynthetic Dynamics with FLUXNET Data and Neural Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Nanyan Zhu
- admin
- Andrew F. Laine
- Jia Guo

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-03-12T00:00:00Z"
# doi: "10.3390/en13061322"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Energies*
publication_short: In *Energies*

abstract: Global warming, which largely results from excessive carbon emission, has become an increasingly heated international issue due to its ever-detereorating trend and the profound consequences. Plants sequester a large amount of atmospheric CO2 via photosynthesis, thus greatly mediating global warming. In this study, we aim to model the temporal dynamics of photosynthesis for two different vegetation types to further understand the controlling factors of photosynthesis machinery. We experimented with a feedforward neural network that does not utilize past histories, as well as two networks that integrate past and present information, long short-term memory and transformer. Our results showed that one single climate driver, shortwave radiation, carries the most information with respect to prediction of upcoming photosynthetic activities. We also demonstrated that photosynthesis and its interactions with climate drivers, such as temperature, precipitation, radiation, and vapor pressure deficit, has an internal system memory of about two weeks. Thus, the predictive model could be best trained with historical data over the past two weeks and could best predict temporal evolution of photosynthesis two weeks into the future.

# Summary. An optional shortened abstract.
summary: By using recurrent models to forecast photosynthetic events, we identify shortwave radiation among six climate drivers as the the most influential predicting factor, and estimate the temporal effect of photosynthesis to be approximately two weeks.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Published Online (Free Download)
  url: https://www.mdpi.com/1996-1073/13/6/1322/htm

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

# Almetric and Dimension badges
add_badge: true

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
          data-doi="10.1016/j.evolhumbehav.2014.06.008" 
          data-hide-zero-citations="true" 
          data-legend="always">
        </span>
      <script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>
        <div  style="float:right"; 
          data-link-target="_blank" 
          data-badge-details="right" 
          data-badge-type="medium-donut"
          data-doi="10.1016/j.evolhumbehav.2014.06.008"   
          data-condensed="true" 
          data-hide-no-mentions="true" 
          class="altmetric-embed">
        </div>
    </div>
    <div id="inner">
      <script type="text/javascript" src="//cdn.plu.mx/widget-summary.js"></script>
        <a href="https://plu.mx/plum/a/?doi=10.1016/j.evolhumbehav.2014.06.008" 
          data-orientation="horizontal" 
          class="plumx-summary" 
          data-site="plum" 
          data-hide-when-empty="true">
        </a>
    </div>
  </section>