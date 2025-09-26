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
        <div class="table-responsive">
          <table class="table table-striped">
            <thead>
              <tr>
                <th>成员类型</th>
                <th>人数</th>
                <th>备注</th>
              </tr>
            </thead>
            <tbody>
              <tr><td>研究员</td><td>5</td><td>含 PI</td></tr>
              <tr><td>访问学者</td><td>2</td><td>本年度</td></tr>
              <tr><td>研究生</td><td>8</td><td>博士+硕士</td></tr>
            </tbody>
          </table>
        </div>
    design:
      columns: '1'
---