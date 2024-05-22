# A-B-testing

This repo consists of a complete A/B testing procedure on a Kaggle dataset. 

# Background
Company XYZ places significant emphasis on the design of its landing page and aims to enhance its conversion rate through improvements in its layout. Historically, the company has maintained an average annual conversion rate of 13%. However, it now seeks to achieve a higher conversion rate with the introduction of a new page design. The company anticipates that the new design will yield a 2% increase, resulting in a target conversion rate of 15%. Prior to the official launch of the new page, the company desires that data scientists conduct a small-scale A/B test to ensure that the anticipated improvements are realized.

# Table of content
- Determine metric
- Propose hypothesis
- Determine experiment groups
- Calculate Minimum sample size & experiment duration
- Data cleaning
- Statistical Testing

# Result Evaluation
Given that the p-value (0.61) substantially exceeds the alpha threshold (0.05), we lack sufficient evidence to reject the null hypothesis. This suggests that the new landing page does not yield a significant difference compared to the old landing page.

Additionally, examining the confidence interval for the treatment group [0.117, 0.136], we find that:
- The baseline conversion rate (0.13) falls within this range.
- However, the target conversion rate (0.15) is outside of this interval.

As a result, we can conclude that the new landing page does not represent a notable improvement and should not be implemented.
