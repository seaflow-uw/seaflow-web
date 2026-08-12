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
  #         size: fill

  - block: slider
    content:
      slides:
      
      - title: 
        content: 'We study how phytoplankton grow, survive, and regulate marine ecosystems as environmental conditions change.'
        align: left
        background:
          image:
            filename: cruisetracks.jpg
            filters:
              brightness: 0.75
          position: center
          color: '#555'
        # link:
        #   icon: users
        #   icon_pack: fas
        #   text: Meet the Team
        #   url: ../people/
        #   #url: https://doi.org/10.5281/zenodo.2678021
          
      - title: 
        content: 'We deploy shipboard flow cytometers, called SeaFlow, that measure the optical properties of individual cells across thousands of miles of ocean.'
        align: left
        background:
          image:
            color: white
            filename: Pro_Diameter.png
            size: contain
            filters:
              brightness: 0.75
          position: center
          color: '#e0e0e0'
        # link:
        #   icon: hard-drive
        #   icon_pack: fas
        #   text: Meet the Instrument
        #   url: ../instrument/
          
      - title: 
        content: 'We combine these observations with mathematical and statistical models to quantify their growth and survival.'
        align: left
        background:
          image:
            filename: MatrixPopulationModel.png
            size: contain
            filters:
              brightness: 0.5
          position: center
          color: '#ffffff'
        # link:
        #   icon: github
        #   icon_pack: fab
        #   text: Open-source Software
        #   url: ../software/

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 7000

  # - block: collection
  #   content:
  #     title: Latest Articles
  #     text: ""
  #     count: 3
  #     filters:
  #       folders:
  #         - publication
  #   design:
  #     view: compact
  #     columns: '1'
  #     spacing:
  #        padding: ['40px', '0', '40px', '0']


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
