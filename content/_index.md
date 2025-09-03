---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title:
        信息安全实验室
        
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        信息安全实验室成立于 2024 年,专注对称密码的安全性分析与设计、面向抗量子计算的哈希算法的安全性分析等方向。  
        团队现有副研究员 1 人，硕博研究生 3 人，承担研发项目、基金多少余项。
        欢迎网络空间安全、信息安全、密码科学与技术、数学、计算机等相关专业的推免生、统考生加入我们。
  
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
