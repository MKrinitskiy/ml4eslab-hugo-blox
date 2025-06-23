---
# Leave the homepage title empty to use the site title
title:
date: 2025-06-20
type: landing

sections:
  - block: hero
    content:
      title: |
        Лаборатория машинного обучения в науках о Земле
      image:
        filename: ML4ESlab-logo.jpeg
      text: |
        <br>       
        Лаборатория машинного обучения в науках о Земле (ML4ES Lab) была основана в октябре 2023 года. Мы изучаем методы оптимального применения машинного обучения для решения прикладных и фундаментальных задач океанологии, наук об атмосфере и климате. Мы создаем модели, которые помогают лучше понимать и прогнозировать процессы земной климатической системы. С применением методов машинного обучения и глубокого обучения мы занимаемся фундаментальными исследованиями и прикладными проектами в области экологии и окружающей среды.
  
  # - block: collection
  #   content:
  #     title: Новости
  #     subtitle:
  #     text:
  #     count: 3
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: Публикации
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Наша команда →" %}}
    design:
      columns: '1'
---
