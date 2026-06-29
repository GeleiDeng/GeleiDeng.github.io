---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-05-24
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
    id: papers
    content:
      title: Featured Research
      filters:
        folders:
          - publication
        featured_only: true
      count: 6
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: Research artifacts, open-source systems, and security testing frameworks from my recent work.
      filters:
        folders:
          - project
      count: 6
    design:
      view: article-grid
      fill_image: false
      columns: 3
  - block: collection
    content:
      title: Recent Publications
      text: ""
      count: 12
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
