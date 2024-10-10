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
        text: Download Resume
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
      text: |-
        I'm currently working to control the rheology of bioinks in 3D bioprinting, to optimize biomanufactured tissues and organs made up of precisely patterned cells. I've designed a magnetic stress rheometer (MSR) to measure the rheology of biomaterials like bioinks and abscess fluids. My research is supported by the <a href="https://www.nsfgrfp.com/">NSF Graduate Research Fellowship</a>!
        <br>

        During my undergrad, I worked with <a href="https://dattalab.princeton.edu/">Professor Sujit Datta</a> at Princeton University to understand the flow of polymer solutions in porous media, useful in cleaning up groundwater in aquifers. I was featured in news articles about <a href="https://acee.princeton.edu/acee-news/people-spotlight-audrey-shih/">my junior year research</a>, and <a href="https://www.princeton.edu/news/2020/06/08/senior-thesis-project-probes-intricacies-groundwater-cleanup">my senior thesis</a>!
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
      count: 0
      # Page type to display. E.g. post, talk, publication...
#      page_type: talk
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
        Outside of the lab, I play clarinet and piano and dabble in conducting, composing, and arranging. I love experimenting new instruments, techniques, and styles of music!
        
        I also like making stuff at the intersection of art and engineering. See some of my music and art projects below.
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
