---
title: Courses & Seminars
type: landing
slug: courses-and-seminars
url: /courses-and-seminars/
summary: Central hub for course attendance, invited seminars, and other trainings.

design:
  spacing: '5rem'

sections:
  - block: collection
    content:
      title: Attendance to research courses & seminars
      text: ''
      filters:
        folders:
          - courses-and-seminars/attendance
    design:
      view: article-grid
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: false
  - block: collection
    content:
      title: Invited seminars & research meetings
      text: ''
      filters:
        folders:
          - courses-and-seminars/invited-seminars
    design:
      view: article-grid
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: false
  - block: collection
    content:
      title: Additional courses
      text: ''
      filters:
        folders:
          - courses-and-seminars/additional-courses
    design:
      view: article-list
      show_date: false
      show_read_time: false
      show_summary: true
      show_read_more: false
---