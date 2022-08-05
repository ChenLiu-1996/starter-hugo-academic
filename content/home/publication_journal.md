---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 8

title: Journal Publications
subtitle: ''

content:
  # Filter on criteria
  filters:
    folders:
      - publication
    tag: ''
    category: ''
    # Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
    # 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
    # 7 = Thesis; 8 = Patent
    publication_type: '2'
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
design:
  # Choose a view for the listings:
  view: 2
  columns: '2'
---

{{% callout note %}}
Quickly discover relevant content by [filtering publications](./publication/).
{{% /callout %}}
