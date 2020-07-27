# Exam 2



-   Numerical Data
    -   Raw data. Real numbers
    -   Summarized data. Mean/average, std. dev., etc

1.  Describe the sampling distribution. This is the theory.
    The problem gave you $\mu$, gave you $\sigma$
    Explain using shape, center, spread
    If sample is bigger than 30, or if the population is normal, then the sample is normal. This describes the sample's shape.
    The center is $\mu$
    Spread is the standard error, found by $\sigma\over\sqrt n$

2.  Build a CI around $\mu$. This is inferential statistics.
    use technology
    The interpretation of a CI is about the population
    You MUST say "TRUE MEAN"/"POPULATION MEAN"/etc

3.  Have you met normality assumption?
    Either check sample size, or build an NPP, ensure that the $p>0.05$

4.  What if the sample size increased?
    $$
    \overline x\pm (t_{crit})({s\over\sqrt n})\\
    $$
    explain that n changes

5.  What if the confidence interval changes?
    explain that t is changing

-   Categorical Data
    -   Mentions count
    -   Mentions percentage

1.  Describe sampling distribution.
    Shape: if $n(p)(1-p)\ge10$ :ballot_box_with_check:
    center:$p$
    spread: $SE\sqrt{\frac{p(1-p)}{n}}$

2.  Build a CI about P
    use $\hat p$ to talk about $p$
    $$
    \hat p\pm(Z_{crit})(\sqrt{\frac{\hat p(1-\hat p)}{n}})
    $$
    1.645=Z for 90%

    1.96=z for 95%

    2.576= z for 99%

    This is important for estimating sample size
    Ensure that the interpretation is about the tru proportion

3.  Normality Assumption?
    see q1 shape



## Followup questions

1.  The true mean of RIT credit card student debt is betwee $$150 and  $3500
2.  Is $2k reasonable? Yes.
3.  Is AT MOST $2k reasonable? No.



Numerical:

1.  Find N.
    given: std. dev, confidence level, margin of error
    calculate as such:
    $$
    n=(\frac{S*Z}{ME})^2\ (round\ up)
    $$

Categorical data:

1.  Find N.
    given: $\hat p$ (if not given, use 0.5), level of confidence, and margin of error
    Calculate as such:
    $$
    n=(\hat p)(1-\hat p)(\frac{Z}{ME})^2
    $$
    

# Exam information:

Part 1 will be on mycourses, and will be 10 questions

part 2 will be in the content portion of MyCourses, and will need to be downloaded.



The exam will require you to use Technology, and will cover:

-   CI
-   Normal Distribution
-   NPP