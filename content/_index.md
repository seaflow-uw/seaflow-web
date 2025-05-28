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
      
      - title: The SeaFlow Research Group
        content: 'We combine observational technologies and statistical approaches to understand how phytoplankton respond to our changing planet and shape the future of marine ecosystems.'
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
        content: 'SeaFlow, our custom-built automated flow cytometer that continuously samples marine phytoplankton, has collected over 800 billion single-cell observations across ocean basins equivalent to six circumnavigations.'
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
          
      - title: Computational Tools and Statistical Analysis
        content: 'Our computational and statistical methods use SeaFlow data to understand how environmental factors influence phytoplankton growth and mortality, shaping community structure and carbon cycling.'
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
      interval: 8000

  - block: markdown
    content:
      title: Latest News
      text: You can purchase or rent SeaFlow for your research cruises and [contact us](mailto:ribalet@uw.edu) to discuss your research needs and join the SeaFlow community.
        {{% cta cta_link="./instrument/" cta_text="Meet the Instrument →" %}}
        
    design:
      spacing:
         padding: ['40px', '0', '40px', '0']

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
