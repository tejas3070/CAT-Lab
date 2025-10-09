---
# Leave the homepage title empty to use the site title
title: 
date: 2025-10-08
type: landing

sections:
  - block: hero
    content:
      title:
      image:
        filename: welcome.jpg
      text: |
        **CAT Lab** is dedicated to advancing the **Compiler, Architecture, and Toolkit (CAT)** foundations that power the next generation of intelligent systems.

        Our research spans the full computing stack — from hardware architecture to compiler design, from performance profiling tools to AI-driven optimization frameworks. 

        We aim to build an efficient and user-friendly infrastructure that helps enhance computational performance across diverse computing platforms.

  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: news
    design:
      view: card
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: Featured Publications
      text: ""
      count: 7
      filters:
        folders:
          - publication
        featured_only: true  
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
