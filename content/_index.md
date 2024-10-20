---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: white
        text_color_light: false
        image:
          # Add your image background to `assets/media/`.
          filename: 
          filters:
            brightness: 0.3
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        <div style="text-align: justify; line-height: 1.6; margin-bottom: 20px; max-width: 1000px; margin-left: auto; margin-right: auto;">
        I use advanced quantitative methods like difference-in-difference and instrumental variables to explore the strategic decisions firms make when commercializing new technologies, including technology transfer, licensing, and strategic alliances.
        </div>
        
        <div style="text-align: justify; line-height: 1.6; margin-bottom: 20px; max-width: 1000px; margin-left: auto; margin-right: auto;">
        My research also addresses challenges in impact investing and family business strategies in Africa, combining privately collected data with survey insights and archival source.
        </div>
        
    
    design:
      columns: '1'
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Working Papers
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
