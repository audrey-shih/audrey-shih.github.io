---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-10-02
type: landing

design:
  # Default section spacing
  spacing: "4.5rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: /uploads/resume.pdf
        attributes: 
          class: "btn-download"
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
  - block: collection
    id: research
    content:
      title: '📚 Research'
      subtitle: ''
      text: |-
        <p class="full-align-indented">Drainage of abscess fluids often fails because physicians don't have a way to predict which catheter size is suitable. I've built a low-cost, portable, sterilizable magnetic stress rheometer that can be deployed to hospitals to solve this issue. With <1 mL of a sample of abscess fluid, I can use my instrument to model the fluid and predict its drainage rate, enabling physicians to personalize treatment plans for each patient.
        
        <p class="full-align-indented">I'm also working on controlling the rheology of bioinks in 3D bioprinting to optimize biomanufactured tissues and organs. My research is supported by the <a href="https://www.nsfgrfp.com/" style="text-decoration: underline;font-weight: bold;">NSF Graduate Research Fellowship</a>!
        <br>

        <p class="full-align-indented">During my undergrad, I worked with <a href="https://dattalab.princeton.edu/" style="text-decoration: underline;font-weight: bold;">Professor Sujit Datta</a> at Princeton University to understand the flow of polymer solutions in porous media, useful in cleaning up groundwater in aquifers. My junior work and senior thesis were featured in the news articles below!
      filters:
        folders:
          - research
    design:
      view: article-grid
      columns: 2
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
      count: 0
      filters:
        #featured_only: false
        folders:
          - talks
    design:
      view: article-grid
      columns: 3
#  - block: collection
#    id: teaching
#    content:
#      title: 👩🏻‍🏫 Teaching
#      filters:
#        folders:
#          - teaching
#    design:
#      view: article-grid
#      columns: 2
  - block: collection
    id: creative
    content:
      title: 🎵 Creative Projects
      text: |-
        <p class="center-align">Outside of the lab, I play clarinet and piano and dabble in conducting, composing, and arranging. I love experimenting with new instruments, techniques, and styles of music. I also like making science-inspired art.
        <br>
        <br>
        See some of my music and art projects below!
      count: 0
      filters:
        folders:
          - creative
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
