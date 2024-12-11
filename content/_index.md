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
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    id: news
    content:
      title: Recent News
      text: |
      - 📃 Our work Reasoning and Explanation Generation in Ad Hoc Collaboration Between Humans and Embodied AI will be presented at the International Conference on Logic Programming and Non-monotonic Reasoning (LPNMR) 2024!
    # date: 2024-08-11
    design:
      columns: '1'
      spacing:
        padding: [2, 0, 0, 0]
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
---
