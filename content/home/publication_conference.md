---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 8

title: Conference Papers
subtitle: ''

content:
  # Filter on criteria
  filters:
    folders:
      - publication
    tag: 'conference'
    category: ''
    # Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
    # 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
    # 7 = Thesis; 8 = Patent
    publication_type: '1'
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
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  #   5 = Showcase
  view: chen_publication
  columns: '2'
---

{{% callout note %}}
Quickly discover relevant content by [filtering publications](./publication/).
{{% /callout %}}
