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
      title: '**Bio**'
      subtitle: ''
      text: |-
Broad undergraduate research experience working in a plant physiological ecology lab - assisting with a range and scale of topics from landscape ecology to photosystem stress physiology in growth chamber experiments. My current work in vertical farming research examines and quantifies crop physiological response to light and other environmental inputs. 

{{< icon name="download" pack="fas" >}} Download my {{< staticref "media/demo_resume.pdf" "newtab" >}}CV{{< /staticref >}}.

    design:
      columns: '1'

<br>
<br>

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
