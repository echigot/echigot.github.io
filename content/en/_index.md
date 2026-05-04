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
        As part of my PhD at **ISAE-SUPAERO**, I taught the following courses to Master students:

        | Course | Level |
        |---|---|
        | Computer Vision — Generative Models | Master |
        | Machine Learning | Master |
        | Object-Oriented Programming | Master |
        | Evolutionary Optimisation | Master |
        | Linux & Python | Master |

        I also supervised **two research interns** (2024, 2025).
    design:
      spacing:
        padding: ['2rem', 0, '2rem', 0]

  - block: markdown
    id: contact
    content:
      title: Contact
      text: |
        **Email:** estelle(dot)chigot(at)gmail(dot)com

        [GitHub](https://github.com/echigot) · [LinkedIn](https://www.linkedin.com/in/estelle-chigot) · [Google Scholar](https://scholar.google.com/citations?user=P6vMCm5Qb7UC)
    design:
      spacing:
        padding: ['2rem', 0, '2rem', 0]
---
