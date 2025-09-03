---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title:
        zh: 信息安全实验室
        en: CyberSecurity Lab
      subtitle:
        zh: 面向前沿 · 聚焦实战 · 开放共享
        en: Cutting-edge · Offensive & Defensive · Open
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        信息安全实验室成立于 **2024 年**，专注MPC/FHE/ZK友好型对称密码的安全性分析与设计、面向抗量子计算的哈希算法的安全性分析等方向。  
        团队现有副研究员 1 人，硕博研究生 3 人，承担研发项目、基金多少余项。
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
