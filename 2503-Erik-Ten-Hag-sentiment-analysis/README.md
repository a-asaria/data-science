# Sentiment analysis of Erik Ten Hag's tenure based on r/reddevils comments

## Goal
There's no better pedigree for a new, young manager joining your team than the Ajax school, and a CV that involves knocking Madrid out of the Champions League. While he broke our many year long trophy drought, saw us beating our city rivals in a cup final, and had Rashford reaching a 30 goal season it wasn't all roses. From expensive signings that are affecting the club still to this day, receiving 25 shots per goal on a regular basis, and our worst PL finish in ages, you can say that his tenure has definitely been a mixed bag

My goal here is to, by running a sentiment analysis on comments on r/reddevils, understand how our collective feeling towards Ten Hag changed over time during his tenure

## Approach
1. Download all historic `r/reddevils` comments via [pushshift]([url](https://www.reddit.com/r/pushshift/))
2. Filter for comments 1) referencing the manager and 2) during his tenure with `filter_eth_comments.py` (based on work by [varunnrao]([url](https://github.com/varunnrao/QuaLLM-Policy)))
