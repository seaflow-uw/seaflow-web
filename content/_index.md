---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # - block: hero
  #   content:
  #     title: <br> <br> <br> <br>
  #   design:
  #     background:
  #       image:
  #         filename: ocean.jpg
  #         parallax: false
  #         position: center
  #         size: cover

  - block: slider
    content:
      slides:
      
      - title: The Ribalet Lab
        content: 'We are a biological oceanography lab at the University of Washington. Our work combines flow cytometry (SeaFlow) and statistical modeling to understand how marine phytoplankton communities respond to environmental change across ocean basins.'
        align: left
        background:
          image:
            filename: ocean.jpg
            filters:
              brightness: 0.75
          position: center
          color: '#555'
        link:
          icon: users
          icon_pack: fas
          text: Meet the Team
          url: ../people/
          #url: https://doi.org/10.5281/zenodo.2678021
          
      - title: High-Resolution Ocean Observations
        content: 'We study marine microbes using our custom SeaFlow flow cytometer that provides continuous, real-time observations of phytoplankton. Over more than a decade, we have collected 800 billion single-cell measurements across nearly six global circumnavigations.'
        align: left
        background:
          image:
            filename: cruisetracks.jpg
            filters:
              brightness: 0.75
          position: center
          color: '#555'
        link:
          icon: hard-drive
          icon_pack: fas
          text: Meet the Instrument
          url: ../instrument/
          
      - title: Population Dynamics Modeling
        content: 'We develop size-structured matrix population models to extract biological rates from SeaFlow time series data. By linking these rates to environmental conditions, we reveal how factors like temperature, nutrients, and light control phytoplankton communities across ocean regions.'
        align: left
        background:
          image:
            filename: MatrixPopulationModel.png
            filters:
              brightness: 0.5
          position: center
          color: '#555'
        link:
          icon: github
          icon_pack: fab
          text: Open-source Software
          url: ../software/

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000

  - block: collection
    content:
      title: Latest Articles
      text: ""
      count: 3
      filters:
        folders:
          - publication
    design:
      view: compact
      columns: '1'
      spacing:
         padding: ['40px', '0', '40px', '0']


# - block: markdown
#     content:
#       title:
#       subtitle: ''
#       text:
#     design:
#       columns: '1'
#       background:
#         image: 
#           filename: coders.jpg
#           filters:
#             brightness: 1
#           parallax: false
#           position: center
#           size: cover
#           text_color_light: true
#       spacing:
#         padding: ['20px', '0', '20px', '0']
#       css_class: fullscreen

---
