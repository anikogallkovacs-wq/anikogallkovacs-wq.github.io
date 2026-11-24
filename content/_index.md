---
title: ''
date: 2024-11-24
type: landing

design:
  spacing:
    padding: ['0', '0', '0', '0']

sections:
  - block: hero
    content:
      title: |
        Munkahelyi jóllét –
        tudományos alapokon
      text: |
        Abban tudok segíteni, hogy a hétfő reggeli ébredés gondolata pont ugyanolyan jó érzéssel töltsön el, mint a péntek esti pihenésé.

        <br>

        Gáll Anikó vagyok, munkahelyi jóllét kutató és HR szakértő. Ezen az oldalon megosztom a kutatási eredményeimet és a szakirodalom legfontosabb felismeréseit – közérthetően.
    design:
      css_class: 'dark'
      background:
        color: '#1a1a2e'

  - block: about.biography
    id: about
    content:
      title: Rólam
      username: admin

  - block: collection
    id: posts
    content:
      title: Tudástár
      subtitle: Kutatásalapú írások a munkahelyi jóllétről
      text: ''
      count: 5
      filters:
        folders:
          - post
        exclude_featured: false
    design:
      view: article-grid
      columns: 2

  - block: markdown
    id: phd
    content:
      title: PhD kutatás
      subtitle: Munkahelyi jóllét gyakorlatok bevezetése
      text: |
        A doktori kutatásom azt vizsgálja, milyen szervezeti kultúra, vezetői szemlélet és megvalósítási stratégia szükséges ahhoz, hogy egy munkahelyi wellbeing program valóban működjön.

        [Bővebben a kutatásról →](phd/)

  - block: contact
    id: contact
    content:
      title: Kapcsolat
      text: Ha kérdésed van, vagy együttműködésben gondolkodsz, keress bátran.
      email: ide.ird@az.emailed.hu
      autolink: true
    design:
      columns: 2
---
