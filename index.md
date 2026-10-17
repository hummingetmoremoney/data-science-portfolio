---
title: Cui Hengming — Data Science Portfolio
---

# Cui Hengming

I am a master's student at the University of Macau. My coursework sits between statistics
and data visualisation: regression and model evaluation in Python, statistical learning in R,
and a fair amount of time spent on how a chart can mislead even when the numbers are correct.
I like projects where the data is public, the code is short enough to read, and the answer
can be checked by someone else.

This site is my portfolio. It is built from this repository with GitHub Pages, deployed from
the `main` branch.

## At a glance

- **Question.** In a country where electric cars have just passed 1% of new car sales, how long
  does it take to reach 10%?
- **Answer.** A median of four years across the 45 markets that made it, with the whole range
  between one and seven years.
- **Caveat.** That median counts only markets that arrived, so it is too optimistic: Japan
  passed 1% in 2017 and is still at 3% today.

## Technical skills

- **Python** — pandas for cleaning and reshaping, matplotlib for charts, scikit-learn for
  linear and polynomial regression, train/test split and cross-validation
- **R** — regression, logistic models, and statistical coursework; tidy data handling
- **Data visualisation** — chart design and critique (Cairo's framework), colour-blind-safe
  palettes, small multiples, annotated rather than decorative charts
- **Workflow** — Jupyter Notebook, Git and GitHub, reproducible scripts with a requirements
  file, writing documentation that another person can follow

## Project showcase

### How fast do car markets switch to electric?

**Research question.** Once electric cars pass 1% of new car sales in a market, how many
years does that market need to reach 10% — and where do the 60 markets in the data stand at
the end of the series?

**Status:** ongoing. The analysis runs end to end, the two figures are final, and the next
step is to bring in a policy variable (purchase incentives, charging density) to test whether
the timing of the fall-backs can be explained.

![Once a market passes 1%, reaching 10% takes one to seven years](images/fig1_time_to_10pct.png)

**What the chart shows.** Each grey line is one market, shifted so that year 0 is the year it
first passed 1% of new sales. The four coloured lines are examples chosen for their speed.
Forty-five of the sixty markets reached 10% before the series ends, and the median gap is four
years; the fastest markets took one year and the slowest took seven. The interesting part is
how narrow the band is: countries with very different incomes and policies still cluster
between three and five years.

![Electric share of new car sales in 2025](images/fig2_share_2025.png)

**The other side of the story.** The end point is much more unequal than the transition.
In 2025 eight markets are above 50% of new sales — Norway at 97%, China at 53% — while
fourteen are still below 10%, including Japan at 3% and India at 4%. The world figure of 25%
is not the typical market: the unweighted mean across markets is 23.9%, because China alone
accounts for more than half of global car sales.

One limitation is written into the method: the 1% → 10% gap can only be measured for markets
that arrived, so the four-year median is too optimistic. Japan passed 1% in 2017 and is still
at 3% eight years later.

[Project repository and full documentation →](https://github.com/hummingetmoremoney/data-science-project)

The repository holds the script, the source CSV, both figures at 200 dpi, and a README with
the data citation, the licence terms, and the commands needed to reproduce the output.

## Contact

GitHub: [@hummingetmoremoney](https://github.com/hummingetmoremoney)
