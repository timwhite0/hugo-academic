---
title: MLBdash
summary: R Shiny dashboard with projected MLB standings and team statistics dating back to 1998.
date: '2022-07-01'

# Optional external URL for project (replaces project detail page).
external_link: ''

links:
url_code: 'https://github.com/timwhite0/MLBdash'
url_pdf: ''
url_slides: ''
url_video: ''

links:
- name: R Shiny
  url: https://twhit.shinyapps.io/MLBdash/
---

[MLBdash](https://twhit.shinyapps.io/MLBdash/) is an R Shiny dashboard with team statistics and projected standings for the 2023 MLB season.

- The first tab lists each team's projected wins and losses, which are the average of the projections from [Baseball Reference](https://www.baseball-reference.com/leagues/majors/2022-playoff-odds.shtml) and [Baseball Prospectus](https://www.baseballprospectus.com/standings/).
- The second tab contains a plot of OPS+ (offensive performance) versus ERA+ (pitching performance) and assigns teams to tiers by partitioning the coordinate space of this plot.
- The third tab presents the information from the first two tabs for every season since 1998, which was the first season in which the MLB expanded to 30 teams.

MLBdash will be updated for the 2024 season in April of 2024.