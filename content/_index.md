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
        url: uploads/Hasra_Dodampegama_CV.pdf
    # design:
    #   css_class: light
    #   background:
    #     color: white
        # image:
          # Add your image background to `assets/media/`.
          # filename: stacked-peaks.svg
          # filters:
          #   brightness: 1.0
          # size: cover
          # position: center
          # parallax: false
  - block: collection
    id: news
    content:
      title: Recent News
      text: ""
      filters:
        folders:
          - news
    design:
      view: date-title-summary
      spacing:
        padding: [2, 0, 0, 0]
  - block: collection
    id: papers
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
      count: 6
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: article-grid
      columns: 2
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
---
