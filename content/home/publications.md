---
# An instance of the Collection block. `pages` was the pre-v5 name for this and
# still resolves, but the current name gets the archive link below.
widget: collection
active: true  # Activate this block? true/false

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 90

title: Recent Publications
subtitle: ''

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: publication
  # Choose how many pages to display (0 = all pages)
  count: 5
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
  # Show journal articles here; working papers and reports live on the full list.
  filters:
    tag: ''
    category: ''
    publication_type: 'article-journal'
    author: ''
    exclude_featured: false
  archive:
    enable: true
    link: publication/
    text: All publications
design:
  # Choose a view for the listings:
  #   1 = List, 2 = Compact, 3 = Card, 4 = Citation (publication only)
  view: 4
---
