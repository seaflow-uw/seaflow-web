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
      
      - title: 
        content: 'We study how marine phytoplankton communities respond to environmental change and regulate the global carbon cycle.'
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
        content: 'We use our custom-built SeaFlow cytometer at sea to measure phytoplankton continuously in real time across ocean basins.'
        align: left
        background:
          image:
            filename: dusk.jpg
            filters:
              brightness: 0.75
          position: center
          color: '#555'
        # link:
        #   icon: hard-drive
        #   icon_pack: fas
        #   text: Meet the Instrument
        #   url: ../instrument/
          
      - title: 
        content: 'We build statistical models to understand how the environment influences phytoplankton growth and community dynamics.'
        align: left
        background:
          image:
            filename: MatrixPopulationModel.png
            filters:
              brightness: 0.5
          position: center
          color: '#555'
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

  - block: collection
    content:
      title: Featured Articles
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
