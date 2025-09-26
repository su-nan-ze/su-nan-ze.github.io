---
title: 团队成员
date: 2022-10-24
type: landing

sections:
  - block: people
    content:
      title: 团队成员
      user_groups:
        - Principal Investigators
        - Researchers
        - Students
        - Administration
        - Visitors
        - Alumni
        - 研究员
        - 访问学者
        - 研究生
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

    - block: markdown
    content:
      title: 团队统计
      text: |
        {{% table %}}
        | 成员类型 | 人数 | 备注         |
        |----------|------|--------------|
        | 研究员   | 5    | 含 PI        |
        | 访问学者 | 2    | 本年度       |
        | 研究生   | 8    | 博士+硕士    |
        {{% /table %}}
    design:
      columns: '1'
---