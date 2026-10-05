# NBA Style of Play

**[See the report →](https://carterterickson.github.io/Sports_Data_Science/)** · [Slides (.pptx)](NBA%20Teams'%20Style%20of%20Play.pptx)

Groups the 30 NBA teams from the 2020-21 season into play styles using clustering.

## What it does

1. Pulls team stats from Basketball Reference and play-by-play stats from PBP Stats.
2. Uses LASSO regression to keep the stats that matter.
3. Runs k-means clustering on three stat groups: box score, shooting and assists, and rebounding and pace.
4. Plots each team on its cluster map.

## Files

| File | What it is |
|---|---|
| `index.html` | The finished report (same as `NBA-Style-of-Play-Project 2.html`) |
| `NBA Style of Play Project.Rmd` | R Markdown source |
| `NBA Teams' Style of Play.pptx` | Presentation slides |

## Tools

R: rvest, dplyr, glmnet, cluster, mclust, ggplot2.

Built for STAT 495R at BYU, December 2021.
