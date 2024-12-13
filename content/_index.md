---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: The Role of Phytoplankton in a Changing Planet
      text: The SeaFlow Research Group is an interdisciplinary team of scientists dedicated to understanding the role of phytoplankton in a changing planet. Phytoplankton are the invisible engines of our oceans, driving the biological carbon pump that helps regulate Earth's climate. Our research focuses on developing innovative observational technologies and advanced computational approaches to understand how these microscopic photosynthetic organisms respond to and influence climate change.

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
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: database
          icon_pack: fas
          text: Download Data
          url: https://doi.org/10.5281/zenodo.2678021
          
      - title: Observational Technology and Computational Tools
        content: 'Continuous Flow-Cytometer, Matrix Population Models'
        align: left
        background:
          image:
            filename: cell-laser.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Open-source Software
          url: ../software/

      # - title: Interdisciplinary Team
      #   content: 'Biological Oceanography, Statistics, Computer Science, Engineering'
      #   align: right
      #   background:
      #     image:
      #       filename: coders.jpg
      #       filters:
      #         brightness: 0.5
      #     position: center
      #     color: '#333'
      #   link:
      #     icon: graduation-cap
      #     icon_pack: fas
      #     text: Meet the Team
      #     url: ../people/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 6000

  - block: markdown
    content:
      title: Latest News
      subtitle:
      text: Transform your phytoplankton research with SeaFlow, our innovative flow cytometer that operates continuously underway. Own a SeaFlow or rent it for your upcoming research expeditions - [contact us](mailto:ribalet@uw.edu) to discuss your research needs and how to become a part of the SeaFlow community.
        {{% cta cta_link="./instrument/" cta_text="Meet the Instrument →" %}}


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