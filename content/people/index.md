---
title: People

type: landing

sections:
  - block: markdown
    content:
      title: <br><b>Meet the Lab</b>
    design:
      columns: '1'
      background:
        image:
          filename: background-4.jpg
        filters:
          brightness: 0

  - block: people
    content:
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Research Faculty
          - Graduate Research Assistants
          - Undergraduate and Post-Baccalaureate Research Assistants
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: false
      show_social: false
---