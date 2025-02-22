# Diamonds-dataset-and-ANOVA

# An overview of ANOVA
The intuition behind ANOVA is to compare the variability between different groups with the variability within the groups. If they are comparable, then the differences between groups are more likely to be due to sampling variability. On the other hand, if the variability between groups is much larger than the variability expected from the samples within their respective groups, then those groups are probably drawn from significantly different subpopulations.

The variation between groups and within groups is calculated as sums of squares, which are then expressed as a ratio. This ratio is known as the F-statistic. The formula for each component of these calculations is presented in the worked example that follows.

Previously, you learned about one-way and two-way ANOVA. To review:

$One-way ANOVA$: Compares the means of one continuous dependent variable based on three or more groups of one categorical variable

$Two-way ANOVA$: Compares the means of one continuous dependent variable based on three or more groups of two categorical variables


ANOVA tests are statistical tests that examine whether or not the means of a continuous dependent variable are significantly different from one another based on the different levels of one or more independent categorical variables. 

It is sufficient for one group’s mean to be significantly different from the others to reject the null hypothesis; however, ANOVA testing is limited in that it doesn’t tell you which group is different. To make such a determination, other tests are necessary. 

ANOVA works by comparing the variance between each group to the variance within each group. The greater the ratio of variance between groups to variance within groups, the greater the likelihood of rejecting the null hypothesis.

ANOVA depends on certain assumptions, so it is important to check that your data meets them in order to avoid drawing false conclusions. At the very least, if your data does not meet all of them, identify these violations.
