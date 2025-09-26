---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title:
        The Cryptography and Information Security Laboratory
        
      image:
        filename: welcome.jpg
      text: |
        <br>
        
         intro
  
  - block: collection
    content:
      title: News
      subtitle:
      text:
      count: 1
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
    title: publications
    count: 5
    filters:
      folders:
        - publication
      publication_type          # 注意去掉单引号
        - article              # 期刊论文
        - conference           # 会议论文
        - preprint             # 预印本
        - book                 # 专著
        - paper
    offset: 0
    order: desc
    design:
    view: citation
    columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="团队成员 →" %}}
    design:
      columns: '1'
---
