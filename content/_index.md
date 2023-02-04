---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: 
    design:
      background:
        video:
          path: intro.mp4
          flip: true
        color: black
      columns: '1'
      css_class: d-flex align-items-center fullscreen
  - block: markdown
    content:
      title: 'Bio'
      subtitle: '______________________________________________________________________________________________________________________________________________________________________________________________________________'
      text: |-
        Broad research and industry experience, with a primary focus on plant physiology in hydroponic production systems. My current research centers around methods of hydroponic fertilizer solution management in vertical farms to identify best-practices for reducing water and fertilizer waste. 
    design:
      columns: '1'

  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '1'
---
<br>