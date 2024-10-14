---
title: Recent & Upcoming Talks
cms_exclude: true
type: landing
#url: talk

output: 
  html_document:
    includes:
       in_header: GA_Script.html
       
cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: talks
    content:
      title: 💬 Recent & Upcoming Talks
      filters:
        folders:
          - talks
    design:
      view: card
      columns: 3

# Optional cover image (relative to `assets/media/` folder).
image:
  caption: ''
  filename: ''
---
