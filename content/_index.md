---
title: ''
summary: ''
date: 2024-01-01
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/CV_Iason_Ofeidis.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      date_format: 'Jan 2006'
      name:
        size: md
      avatar:
        size: xl
        shape: circle
  - block: markdown
    id: contact
    content:
      title: ''
      subtitle: ''
      text: |-
        **Contact:** iason.ofeidis &lt;at&gt; yale.edu
    design:
      columns: '1'
  - block: resume-awards
    id: awards
    content:
      title: Awards
      username: me
  - block: collection
    id: publications
    content:
      title: Publications
      text: 'Also available on [Google Scholar](https://scholar.google.com/citations?user=wOGPwdMAAAAJ&hl=en).'
      # 0 = show all
      count: 0
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
