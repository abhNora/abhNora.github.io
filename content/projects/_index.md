---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Apply to all project pages
# cascade:
#   reading_time: false

# Page sections
sections:
  - block: collection
    content:
      title: Research projects & working groups
      text: ''
      filters:
        folders:
          - projects
      #cascade:
        #reading_time: false
    design:
      view: article-grid
      fill_image: false
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: false
  - block: collection
    content:
      title: Personal projects
      text: ''
      filters:
        folders:
          - personal-projects
      cascade:
        reading_time: false
    design:
      view: article-grid
      fill_image: false
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: false
---
