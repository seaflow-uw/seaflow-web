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

  - block: markdown
    content:
      text: We are an interdisciplinary team of scientists studying the role of phytoplankton in a changing planet. We integrate advanced observational technologies with innovative computational approaches to understand how phytoplankton respond to changing ocean conditions and what that means for the future of our oceans.
      align: justify
    design:
      spacing:
         padding: ['40px', '0', '40px', '0']

  - block: slider
    content:
      slides:
      - title: High-Resolution Ocean Observations
        content: '800 billion cell measurements of phytoplankton collected across a distance equivalent to six global circumnavigations.'
        align: left
        background:
          image:
            filename: cruisetracks.jpg
            filters:
              brightness: 0.9
          position: center
          color: '#555'
        link:
          icon: database
          icon_pack: fas
          text: Download Data
          url: https://doi.org/10.5281/zenodo.2678021
        
      - title: Computational Tools and Statistical Analysis
        content: 'Data analysis and Visualization, Matrix Population Models, Machine Learning'
        align: left
        background:
          image:
            filename: cell-laser.jpg
            filters:
              brightness: 0.8
          position: center
          color: '#555'
        link:
          icon: graduation-cap
          icon_pack: fas
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

  - block: markdown
    content:
      title: Latest News
      text: Transform your phytoplankton research with SeaFlow, our innovative flow cytometer that operates continuously underway. Own a SeaFlow or rent it for your upcoming research expeditions - [contact us](mailto:ribalet@uw.edu) to discuss your research needs and how to become a part of the SeaFlow community.
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
