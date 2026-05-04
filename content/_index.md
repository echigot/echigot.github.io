---
title: 'Accueil'
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
      title: Publications récentes
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
      title: Projets de recherche
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
      title: Enseignement
      text: |
        Dans le cadre de ma thèse à l'**ISAE-SUPAERO**, j'ai enseigné les matières suivantes à des étudiants de Master :

        | Matière | Niveau |
        |---|---|
        | Vision par ordinateur — modèles génératifs | Master |
        | Apprentissage automatique | Master |
        | Programmation orientée objet | Master |
        | Optimisation évolutionnaire | Master |
        | Linux & Python | Master |

        J'ai également encadré **deux stagiaires de recherche** (2024, 2025).
    design:
      spacing:
        padding: ['2rem', 0, '2rem', 0]

  - block: contact-info
    id: contact
    content:
      title: Contact
      email: 'estelle.chigot@gmail.com'
      autolink: true
    design:
      spacing:
        padding: ['2rem', 0, '2rem', 0]
---
