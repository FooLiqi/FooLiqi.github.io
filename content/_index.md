---
# Leave the homepage title empty to use the site title
title: Home
date: 2024-09-27 
type: landing

sections:
  - block: markdown
    content:
      title: >
        <span style="color: white;">Flexible Autonomy and Robotics Lab</span>
      subtitle: >
        <span style="color: #C0C0C0;">An academic research lab in Hong Kong University of Science and Technology</span>
    design:
      columns: '1'
      background:
        image: 
          filename: ri-view1.jpeg
          filters:
            brightness: 0.6
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['200px', '0', '200px', '0']
      css_class: d-flex align-items-center
      
  - block: markdown
    content:
      title:
      subtitle:
      text: |-
        This research group consists of graduate students in electrical engineering and robotics under the supervision of [Prof. Fumin Zhang](author/fumin-zhang/) at the Hong Kong University of Science and Technology. A few areas of research in which our group is actively engaged are bio-inspired autonomy, human-robot interaction, autonomous underwater vehicles, mobile sensing networks, and cyber-physical systems.
    design:
      columns: '1'
      spacing:
        padding: ['50px', '0', '50px', '0']
        
  - block: collection
    content:
      title: Researchs
      text: ""
      count: 5
      filters:
        folders:
          - project
      sort_by: 'Date'
      sort_ascending: true
    design:
      view: showcase
      columns: '1'
      
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: 'news'
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      # columns: '1'
      flip_alt_rows: false

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        # publication_type: 'article'
    design:
      view: citation
      columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text:
  #   design:
  #     columns: '1'

---
