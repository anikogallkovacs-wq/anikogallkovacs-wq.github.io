---
title: ''
date: 2024-11-24
type: landing

sections:
   - block: resume-biography-3
    content:
      username: admin
      headings:
        about: "Szakmai bemutatkozás"
        education: "Tanulmányok"
        interests: "Szakterületek"
      text: ''
      button:
        text: ''
        url: ''
    design:
      background:
        gradient_mesh:
          enable: true
      avatar:
        size: medium
        shape: circle
      name:
        size: lg

  - block: markdown
    id: phd
    content:
      title: 'PhD kutatás'
      subtitle: 'Munkahelyi jóllét gyakorlatok bevezetése'
      text: |-
        A doktori kutatásom azt vizsgálja, milyen szervezeti kultúra, vezetői szemlélet és megvalósítási stratégia szükséges ahhoz, hogy egy munkahelyi wellbeing program valóban működjön.

        [Bővebben a kutatásról →](phd/)
    design:
      columns: '1'

  - block: collection
    id: posts
    content:
      title: Tudástár
      subtitle: Kutatásalapú írások a munkahelyi jóllétről
      text: ''
      page_type: blog
      count: 5
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
