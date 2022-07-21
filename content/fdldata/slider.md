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
    - title: 👇🏼 Conoce más sobre el proyecto FONDECYT
      content: Mira en lo que estamos trabajando últimamente...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
    - title: Construcción de datos a nivel mundial
      content: 'Desarrollamos una base única que permite comparar relaciones laborales en el tiempo para más de 60 países'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact.jpg
      link:
        icon: globe
        icon_pack: fas
        text: Más sobre los datos
        url: https://fabrica-datos-laborales.github.io/fdl-data/index.html#presentation
---
