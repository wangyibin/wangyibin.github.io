---
title: ''
summary: 'Placeholder project-first academic portfolio.'
date: 2026-07-14
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: 'I am a PhD candidate at the Huazhong Agricultural University, jointly trained at the Agricultural Genomics Institute at Shenzhen, Chinese Academy of Sciences, where I develop computational methods for polyploid genome assembly and chromosome-scale haplotype reconstruction.'
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
      title: "Featured Research"
      subtitle: "C-Phasing"
      text: |-
        [**C-Phasing**](https://wangyibin.github.io/CPhasing) is a chromosome-scale assembly framework for haplotype-resolved reconstruction of polyploid genomes using Hi-C and Pore-C data.

        It integrates graph algorithms, long-read sequencing, chromatin interaction data, and methylation information to improve chromosome reconstruction in complex genomes.

        **[Learn more →](/projects/c-phasing/)**
    design:
      columns: "1"

  - block: collection
    id: projects
    content:
      title: Project
      text: 'Selected research software and methods.'
      filters:
        folders:
          - projects
        exclude_featured: false
    design:
      view: card
      columns: 3

  # - block: markdown
  #   id: research
  #   content:
  #     title: 'Research Interests'
  #     text: |-
  #       Placeholder research interests:

  #       - Computational biology
  #       - Bioinformatics
  #       - Genomics
  #       - Reproducible scientific software
  #   design:
  #     columns: '1'

  # - block: markdown
  #   id: experience-education
  #   content:
  #     title: 'Experience and Education'
  #     text: |-
  #       Placeholder section for experience and education. Replace this with real institutional roles, education history, and selected milestones.
  #   design:
  #     columns: '1'

  - block: collection
    id: recent-publications
    content:
      title: Recent Publications
      count: 3
      sort_by: Date
      sort_ascending: false
      filters:
        folders:
          - publications
      archive:
        enable: true
        text: All publications
        link: publications/
    design:
      view: recent-citation
      columns: 1

---
