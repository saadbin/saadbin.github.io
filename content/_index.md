---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: uploads/Saadbin_Resume.pdf
      headings:
        about: 'About Me'
        education: ''
        interests: ''
    design:
      spacing:
        padding: ['0rem', '0', '0', '0']
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: collection
    id: projects
    content:
      title: Selected Projects
      count: 6
      filters:
        folders:
          - projects
      sort_by: 'weight'
      sort_ascending: true
        #featured_only: true
    design:
      view: article-grid
      columns: 3
  - block: collection
    id: publications
    content:
      title: Selected Publications
      count: 5
      filters:
        folders:
          - publications
      sort_by: 'weight'
      sort_ascending: true
        #featured_only: true
    design:
      view: article-grid
      columns: 3
  # - block: collection
  #   content:
  #     title: Publications
  #     count: 0
  #     text: ''
  #     filters:
  #       folders:
  #         - publications
  #       exclude_featured: false
  #   design:
  #     view: citation
  # - block: collection
  #   id: presentations
  #   content:
  #     title: 'Presentations'
  #     count: 0
  #     filters:
  #       folders:
  #         - presentations
  #   design:
  #     view: citation
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: publications
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 10
  #     # Filter on criteria
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: article-grid
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
---
