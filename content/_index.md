---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: 👋 Welcome to IPC4MH
          content: Developing immersive prevention centers for mental health promotion and early detection.
          align: center
          background:
            image:
              filename: welcome.jpg
              filters:
                brightness: 0.6
            position: center
    design:
      is_fullscreen: true

  - block: hero
    content:
      title: |
        IPC4MH - Immersive Prevention Center for Mental Health
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        IPC4MH is shaping the future of mental health prevention through immersive environments, advanced sensing, and human-centred innovation.
  
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
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
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
