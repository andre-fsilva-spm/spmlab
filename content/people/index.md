---
title: People
date: 2025-07-29

type: landing

sections:

  - block: markdown
    content:
      title:
      subtitle:
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: team.jpg
          filters:
            brightness: 1
          parallax: true
          position: center
          size: actual
          text_color_light: true
      spacing:
        padding: ['90px', '0', '600px', '0']
        
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Researchers
          - Grad Students
          - Post Docs
          - Administration
          - Visitors
          - Alumni
          - Lab Advisors
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
---