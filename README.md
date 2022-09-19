# The Role of Social Distance in Surrogate Decision Making Involving Risks

## About the project

In this project, I cleaned and analyzed the data I collected for my undergraduate honors thesis at Wake Forest University. 

In this research project, I explored whether social distance (also referred to as psychological distance, or closeness of relationship) and decision domain play a role in self-other differences in decision making. 287 students from Introductory Psychology course at Wake Forest University were recruited via the SONA system. Participants were randomly assigned to one of 3 conditions, asking them to decide for **1) self 2) a friend, or 3) a typical Wake Forest Student**. They each read short scenarios in the **monetary and safety domains** (a total of 8 scenarios, 4 for monetary and 4 for safety situations respectively) and chose one from the two options involving different levels of risk taking (risk-seeking vs. risk-averse). The total number of riskier choices was compared across conditions.

Just to provide more background, I am including sample scenarios participants read in the experiment. 

[*Monetary scenario for “self” condition*] You are playing a poker game. Now, you have two options. One option is to end the game immediately. If you choose this option, you will win \$10. Another option is to continue to play the game. If you choose this option, you will win \$100 with a chance of 10% or you will win nothing. Which option would you choose for yourself?

A. End the game to win \$10

B. Continue to play the game to win \$100 with a chance of 10% and win nothing with a chance of 90% 

[*Safety scenario for “friend” condition*] Your friend is riding alone in a taxi. After riding in the taxi for a while, it becomes apparent to them that the driver is drunk. There are no other taxis around or other means of transportation. Their destination is 5 miles away, and although it is inconvenient, it is safe to walk. Which option would you choose for your friend?

A. Get out of the taxi and walk

B. Remain in the taxi

This study was a 3 x 2 repeated-measures design, with **decision recipients** (self vs. friend vs. typical Wake Forest student) as the *between-subjects* factor, and the **decision domain** (monetary vs. safety) as the *within-subjects* factor. The *dependent variable* was **risk preference** in decision making, measured by total number of participants’ risk-taking choices within each domain. Moreover, half of the participants read the monetary scenarios first, while the other half read the safety scenarios first, with order randomly assigned, in order to eliminate order effect.

## Required packages

The following packages were used:

```r
library(tidyverse)
library(here)
library(knitr)
library(rstatix)
```

## Files included

The following files were included in this repository:

* the [R markdown file](data-analysis.Rmd) used to import, tidy, explore and analyze data and render the report,
* the rendered [Markdown document](data-analysis.md) containing the report generated, and
* the [folder](data-analysis_files) containing all the figures created.

*Note: if you need the data, please contact me at wux17@alumni.wfu.edu*