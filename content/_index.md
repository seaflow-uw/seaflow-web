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
        content: 'We are an interdisciplinary team of scientists studying the role of phytoplankton in a changing planet. We integrate advanced observational technologies with innovative computational approaches to understand how phytoplankton respond to changing ocean conditions and what that means for the future of our ecosystems.'
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
        content: 'SeaFlow is an automated cytometer that continuously samples and analyzes marine phytoplankton, providing high-resolution data on their population dynamics across vast ocean scales. Over the last decade, we have collected over 800 billion single-cell observations of phytoplankton across a distance equivalent to six circumnavigations.'
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
        content: 'Our computational tools leverage SeaFlow data and innovative statistical methods to classify phytoplankton, model their growth and carbon uptake, and investigate how environmental factors shape their communities and influence the carbon cycle.'
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
      text: Enhance your phytoplankton research with SeaFlow, our flow cytometer that operates continuously underway. Own or rent it for your upcoming research expeditions - [contact us](mailto:ribalet@uw.edu) to discuss your research needs and how to become a part of the SeaFlow community.
        {{% cta cta_link="./instrument/" cta_text="Meet the Instrument →" %}}
        
        Tired of using an Excel file to plan your next cruise? We created a user-friendly interface for planning research expeditions, allowing scientists to add stations and visualize the track on a map, and manage the cruise schedule. 
        {{% cta cta_link="http://seaflow.shinyapps.io/cruisetrackplanner" cta_text="Cruise Track Planner →" %}}

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
