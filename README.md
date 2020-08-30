## Missing Female HoH

We use the [SECC 2011 data](https://github.com/in-rolls/secc) from 14 states to estimate the percentage of households that have a female Head of Household (HoH), the variation in percentage of female HoH by last name (see [here](https://github.com/appeler/outkast) for how we deduce last names; we limit inference of female HoH by last name to last names shared by at least 1000 households) and by SC/ST/Other. We also estimate the average age of female and male HoH.

About 11.7% of the households have a female HoH. Expectedly, the age of female HoH (~ 54.1 years) is generally higher than a male HoH (~ 47.3 years). The percentage of female HoH doesn't vary much by SC/ST/Other but varies widely across last names, with the 10th percentile being 2% and the 90th percentile being 17.6%.

### Analysis

* [Python notebook](female_hoh.ipynb)

### Authors

Suriyan Laohaprapanon and Gaurav Sood
