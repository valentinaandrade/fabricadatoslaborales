---
widget: slider
weight: 20
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👇🏼 FDL data base
      content: Base de datos a nivel mundial y comparado
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: cubes2.jpg
      link:
      icon: globe
      icon_pack: fas
      text: Descargar datos
      url: https://github.com/fabrica-datos-laborales/fdl-data/raw/main/output/data/fdl.RData
    - title: Libro de Códigos
      content: 'Información sobre las variables de FDL data base'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact2.jpg
      link:
        icon: globe
        icon_pack: fas
        text: Más sobre los datos
        url: https://fabrica-datos-laborales.github.io/fdl-data/index.html#presentation
---
