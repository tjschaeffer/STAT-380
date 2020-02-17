# U.S. Census Modeling

## Instructions

*Article 1 of the United States Constitution actually mandates that a census of the US population be taken every 10 years.  This has various purposes, including reallocation of seats in the U.S. House of Representives based on relative population of each state.  Population growth is typically not linear (as we'll see).*

*You will scrape and clean the US Census data from Wikipedia, and then fit an exponential model of the form:* 

\[y = \frac{\beta_1}{1 + \exp(\beta_2 + \beta_3*x)}\]

*where *y* is the total population in the US at the time of the census taken at time *x*.  This is the model family, and you will use R's `optim` function to estimate the parameters $\beta_1, \beta_2, \& \beta_3$ for the non-linear model that best fits the data.*  
 

## Grading 

### Overall Quality [10 pts] 

The overall quality of the work submitted will be graded in addition to the content of your analysis.  For example, be sure that:** 

- all code is consistent with the STAT 380 Style Guide;
- all plots have informative titles, axis labels, and legends;
- narrative descriptions are well-written.  Lists or bullet points are fine, but the text should be complete sentances free of significant spelling, grammar and other issues.

### Exploring Randomness [50 pts]

| Section | Points Possible |
|:--------|:----------------|
| Part 0 | 1 pt |
| Part 1 | 7 pts |
| Part 2 | 8 pts |
| Part 3 | 8 pts |
| Part 4 | 4 pts |
| Part 5 | 18 pts | 
| Part 6 | 4 pts |

