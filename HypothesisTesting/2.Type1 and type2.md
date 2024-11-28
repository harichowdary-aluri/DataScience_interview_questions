# Type-I and Type-II Errors

In hypothesis testing, there are two types of errors that can occur when making a decision about the null hypothesis:

1. **Type-I Error (False Positive)**
   - It occurs when the sample results lead to the rejection of the null hypothesis when it is in fact true.
     - Example:
       - Null Hypothesis (H0): No crime.
       - Alternative Hypothesis (H1): Crime.
   - Denoted by **α** (alpha), which is the significance level.
   - By choosing the significance level, we can control the risk of making a Type-I error.

2. **Type-II Error (False Negative)**
   - It occurs when our sample results lead to not rejecting the null hypothesis when it is in fact false.
   - Denoted by **β** (beta).

There is a trade-off between Type-I and Type-II errors. If we increase the sample size, the risk of both errors may decrease.

## Additional Notes

- To reject the null hypothesis, the **p-value** should be less than the significance level.
- If the result shows an improvement in an A/B test, we rerun the test with an increase in statistical power.
