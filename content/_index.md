---
title: ''
summary: 'Placeholder project-first academic portfolio.'
date: 2026-07-14
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: 'Placeholder introduction for a project-first academic portfolio. Replace this with a concise description of your research, software, and current role.'
      button:
        text: View CV
        url: cv/
      headings:
        about: ''
        education: 'Education'
        interests: 'Research Interests'
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    id: c-phasing
    content:
      title: 'Featured Project'
      subtitle: 'C-Phasing'
      text: |-
        **C-Phasing** is the lead project for this portfolio.

        Placeholder summary for a computational biology or genomics project. Replace this copy with a concise explanation of what C-Phasing does, who it helps, and where visitors should go next.

        [Open C-Phasing](/CPhasing)
    design:
      columns: '1'

  - block: collection
    id: projects
    content:
      title: More Projects
      text: 'Placeholder project cards for related research software, reproducible workflows, and open source tools.'
      filters:
        folders:
          - projects
        exclude_featured: false
    design:
      view: card
      columns: 3

  - block: markdown
    id: research
    content:
      title: 'Research Interests'
      text: |-
        Placeholder research interests:

        - Computational biology
        - Bioinformatics
        - Genomics
        - Reproducible scientific software
    design:
      columns: '1'

  - block: markdown
    id: experience-education
    content:
      title: 'Experience and Education'
      text: |-
        Placeholder section for experience and education. Replace this with real institutional roles, education history, and selected milestones.
    design:
      columns: '1'

  - block: collection
    id: publications
    content:
      title: Publications
      text: 'Placeholder publications section. Add real publication pages, BibTeX files, or DOI metadata later.'
      filters:
        folders:
          - publications
    design:
      view: citation

  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        Placeholder contact details:

        - Email: [your.email@example.com](mailto:your.email@example.com)
        - GitHub: [your-github-username](https://github.com/your-github-username)
        - Google Scholar and ORCID links can be added when available.
    design:
      columns: '1'
---
