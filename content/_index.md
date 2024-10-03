---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-10-02
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: shriram2.jpg
          filters:
            brightness: 0.3
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: research
    content:
      title: '📚 Research'
      subtitle: 'Exploring Innovations in 3D Bioprinting'
      text: 'I am currently working on projects to control the rheology of bioinks in 3D bioprinting, seeking to optimize biomanufactured tissues and organs made up of precisely patterned cells. My research is supported by the [NSF Graduate Research Fellowship](https://www.nsfgrfp.org/).
      

      During my undergrad, I worked with [Professor Sujit Datta](https://dattalab.princeton.edu/) at Princeton University to understand the flow of polymer solutions in porous media, useful in cleaning up groundwater in aquifers. Read about my junior year research [here](https://acee.princeton.edu/acee-news/people-spotlight-audrey-shih/), and my senior thesis [here](https://www.princeton.edu/news/2020/06/08/senior-thesis-project-probes-intricacies-groundwater-cleanup)!'
    design:
      columns: '1'
#  - block: collection
#    draft: true
#    id: papers
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      view: article-grid
#      columns: 2
  - block: collection
    id: papers
    content:
      title: 📖 Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: 💬 Recent & Upcoming Talks
      filters:
        #featured_only: false
        folders:
          - talks
    design:
      view: article-grid
      columns: 3
  - block: collection
    id: teaching
    content:
      title: 👩🏻‍🏫 Teaching
      filters:
        folders:
          - teaching
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: music
    content:
      title: 🎵 Music Projects
      text: |-
        Outside of the lab, I play clarinet and piano and dabble in conducting, composing, and arranging. I love trying new instruments, techniques, and styles of music!
      filters:
        featured_only: false
        folders:
          - music
    design:
      view: article-grid
      columns: 3
#  - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
#      # Page type to display. E.g. post, talk, publication...
#      page_type: post
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: date-title-summary
#      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]
---
