---
title: Research
type: landing

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
    id: research
    content:
      title: Research
      filters:
        folders:
          - research
    design:
      view: article-grid
      columns: 2
---
