---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: 团队成员
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
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
      title: people
      text: |
        {{< table >}}
        | 成员类型       | 人数 | 备注           |
        |----------------|------|----------------|
        | 研究员         | 5    | 包括PI和研究员 |
        | 访问学者       | 2    | 本年度访问     |
        | 研究生         | 8    | 博士+硕士      |
        | 行政人员       | 1    | 实验室管理员   |
        {{< /table >}}
    design:
      columns: '1'
---
---