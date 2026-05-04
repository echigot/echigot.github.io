---
title: 'Home'
type: landing
sections:
  - block: resume-biography
    content:
      username: admin
    design:
      spacing:
        padding: ['3rem', 0, '3rem', 0]

  - block: collection
    id: publications
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
      count: 5
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: citation
      spacing:
        padding: ['2rem', 0, '2rem', 0]

  - block: collection
    id: projects
    content:
      title: Research Projects
      filters:
        folders:
          - project
    design:
      view: card
      spacing:
        padding: ['2rem', 0, '2rem', 0]

  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |
        *To fill in: your courses, training, supervision.*
    design:
      spacing:
        padding: ['2rem', 0, '2rem', 0]

  - block: contact-info
    id: contact
    content:
      title: Contact
      email: ''
      autolink: true
    design:
      spacing:
        padding: ['2rem', 0, '2rem', 0]
---
