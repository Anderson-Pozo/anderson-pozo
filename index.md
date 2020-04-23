---
title: Home
sections:
  - section_id: hero
    component: hero_block.html
    type: heroblock
    content: >-
      This section can contain a subtitle or tagline. The recommended length is
      one to three sentences, but can be changed as you prefer.
  - section_id: about
    component: content_block.html
    type: contentblock
    title: Sobre mí
    content: >-
      Soy estudiante de la carrera de Ingeniería en Informática, miembro activo de la Upec Microsoft Community. Tengo experiencia en el       desarrollo web y móvil y tengo conocimiento en varios lenguajes de programación como Python, PHP, Java y Javascript.
    actions:
      - label: Contact Me
        url: /contact
  - section_id: recent-posts
    component: posts_block.html
    type: postsblock
    title: Artículos recientes
    num_posts_displayed: 4
    actions:
      - label: View Blog
        url: blog/index.html
menus:
  main:
    weight: 1
    title: Home
layout: home
---
