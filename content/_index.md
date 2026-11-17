---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-01-01
type: landing
  
sections:
  - block: v1/about
    id: about
    content:
      title: Hello!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: compact
  - block: accomplishments
    id: teaching
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Teaching'
      id: teaching
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: '2025-04-01'
          date_start: '2024-08-01'
          description: ''
          organization: Department of Statistics, University of Michigan
          organization_url: ''
          title: DATASCI 451 - Bayesian Data Analysis
          url: ''
        - certificate_url: ''
          date_end: '2024-04-01'
          date_start: '2024-01-01'
          description: ''
          organization: Department of Statistics, University of Michigan
          organization_url: ''
          title: DATASCI 415 - Data Mining and Statistical Learning
          url: ''
        - certificate_url: ''
          date_end: '2023-12-01'
          date_start: '2023-08-01'
          description: ''
          organization: Department of Statistics, University of Michigan
          organization_url: ''
          title: STATS 401 - Applied Statistical Methods II
          url: ''
        - certificate_url: ''
          date_end: '2023-04-01'
          date_start: '2023-01-01'
          description: ''
          organization: Department of Statistics, University of Michigan
          organization_url: ''
          title: STATS 306 - Introduction to Statistical Computing
          url: ''
        - certificate_url: ''
          date_end: '2022-12-01'
          date_start: '2022-08-01'
          description: ''
          organization: Department of Statistics, University of Michigan
          organization_url: ''
          title: STATS 250 - Introduction to Statistics and Data Analysis
          url: ''
    design:
      columns: '2'
  - block: experience
    id: experience
    content:
      title: Work experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Data Science Intern
          company: New York Mets
          company_logo: nym
          location: New York, NY
          date_start: '2022-08-01'
          date_end: '2022-11-01'
          description:
        - title: Intern, Data Science Summer Institute
          company: Lawrence Livermore National Laboratory
          company_logo: llnl
          location: Livermore, CA
          date_start: '2022-05-01'
          date_end: '2022-08-01'
          description:
        - title: Research Assistant, IPUMS International
          company: Minnesota Population Center
          company_logo: mpc
          location: Minneapolis, MN
          date_start: '2019-01-01'
          date_end: '2022-05-01'
          description:
        - title: Intern, Population and Development Branch
          company: United Nations Population Fund (UNFPA)
          company_logo: unfpa
          location: New York, NY (remote)
          date_start: '2021-09-01'
          date_end: '2022-03-01'
          description:
    design:
      columns: '2'
---
