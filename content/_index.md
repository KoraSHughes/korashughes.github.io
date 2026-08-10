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
        text: View Resume
        url: https://docs.google.com/document/d/1HrtfWwI153WX1UtNxkRJzRZ9ZC9D8AehBAdq7alomfQ/edit?tab=t.0
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
  - block: markdown
    content:
      title: '📚 My Research 📚'
      subtitle: ''
      text: |-
        At heart, I am a data scientist interested in applying ML and statistical models toward wearables and robotics interfacing with human health. With the help of my coadvisors <a href="https://users.ece.cmu.edu/~pgrover/lab.html">Pulkit Grover</a> and <a href="https://www.meche.engineering.cmu.edu/directory/bios/weber-douglas.html">Doug Weber</a>, my research is centered around leveraging neurostimulation to make the interaction with and manipulation of brain-machine interfaces like neuroprosthetics more safe, robust, and versatile.

        I hope to develop a range of qualitative and quantitative methods to bolster the role of neural data and other biometrics in human-robot interaction and healthcare.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
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
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Website is Being Updated :(
      text: Sorry but the website is currently being worked on so it is temporarily down. Please check in later! :)
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
