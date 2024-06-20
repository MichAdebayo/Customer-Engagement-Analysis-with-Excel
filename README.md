# Customer-Engagement-Analysis-with-Excel

The project aims at analyzing some customer engagement metrics for 365 Company to determine whether the addition of new features increased student engagement.

## Case Description

In 2022, there were high expectations for the growth of the 365 company and increased student engagement based on the introduction of new website platform features. Some of these features included an XP system that enabled students to track their progress, level up, and earn rewards by completing various learning objectives. The platform also offered in-app coins that could be exchanged for special awards, a leaderboard where students could compete for top positions in different divisions, earning weekly rewards and advancing up the ladder, and streaks to motivate students to maintain consistent learning habits. Additionally, the company expanded its course library, covering a broader range of topics to provide its students with a richer set of skills and attract a larger audience. These enhancements were anticipated to positively impact the student experience, create an effective strategy for customer engagement, and contribute to the company's success in the coming year. With this Customer Engagement Analysis Excel project, I analyze whether the new additions to the platform have increased student engagement.

## Dataset

The dataset for this project comes from the 365 company, hence, it is a real-world dataset that represent low-engagement-paid- and free- plan students of the company’s operations. Note that personal user information has been masked to ensure privacy. The following are the column values available in the dataset: 

* **student_id –** the unique identifier for each student in the dataset. The field contains IDs for students who used the 365 Data Science platform with free or paid accounts in **Q4 2021** (October 1, 2021 – December 31, 2021, both included) and **Q4 2022** (October 1, 2022 – December 31, 2022, both included).

* **student_country –** identifies the country of each student. The field provides information about students’ geographic location and can help analyze regional differences or conduct country-specific analyses.

* **minutes_watched_21 –** represents the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2021.
  
* **minutes_watched_22 –** denotes the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2022.

* **Paid –** indicates whether a student had a paid account during the specified period. It is a binary variable, where '1' represents a paid account and '0' represents a free or unpaid account. It helps differentiate between students who have access to additional features or content through a paid subscription.

## Exploring the difference in engagement between paid- and free-plan subscribers in Q4 2021 and Q4 2022

### **Paid-plan Students**

<div align="center">
<img width="500" alt="Screenshot 2024-06-19 at 16 21 04" src="https://github.com/MichAdebayo/Customer-Engagement-Analysis-with-Excel/assets/92400436/caffa178-890a-4b5f-a55f-9f7f3b858e27">
</div>

* **Mean:** Among students who watched between 1 and 100 minutes in 2021, the average minutes watched by paid-plan students increased significantly from Q4 2021 to Q4 2022, from approximately 33.80 minutes to about 273.02 minutes. This suggests a substantial increase in engagement among this group of initially low-engagement-paid-plan students.

* **Median:** The median minutes these low-engagement-paid-plan students watched increased from Q4 2021 to Q4 2022, from 26.33 minutes to 40.28 minutes. While this increase is not as dramatic as the increase in the mean, it indicates that the typical student in this group (i.e., the student in the middle of the distribution) also increased their engagement. This suggests that the increase in engagement was more widespread among paid-plan students and not solely driven by a few outliers.

* **Standard Deviation:** The standard deviation for these low-engagement-paid-plan students increased substantially from 28.21 minutes in Q4 2021 to 854.58 minutes in Q4 2022. This indicates a much larger variability in the minutes watched by these students in Q4 2022 compared to Q4 2021. This could be due to a broader range of engagement levels among the students in Q4 2022, with some students watching very little content and others watching a lot of content.

These results suggest that paid-plan students who were initially low-engagement in 2021 significantly increased their engagement in 2022. But the increased standard deviation indicates a broader range of engagement levels among these students in 2022. Understanding the reasons behind this variability could provide valuable insights for further boosting engagement. For instance, the factors that motivated the students who significantly increased their engagement might be leveraged to encourage increased engagement among other students.

### **Free-plan Students**

<div align="center">
<img width="504" alt="Screenshot 2024-06-19 at 16 42 59" src="https://github.com/MichAdebayo/Customer-Engagement-Analysis-with-Excel/assets/92400436/00f392f6-7551-479e-8cdc-395cc90fc632">
</div>

* **Mean:** Among students who watched between 1 and 100 minutes in 2021, the average minutes watched by free-plan students increased from about 25.39 minutes in Q4 2021 to about 117.64 minutes in Q4 2022. This suggests that overall engagement among these initially low-engagement-free-plan students increased during this period. But the extent of this increase is less than what was observed for similar low-engagement-paid-plan students, suggesting that while these free-plan students are watching more content, they're still not as engaged as the equivalent group of paid-plan students.

* **Median:** Interestingly, the median minutes watched by these low-engagement-free-plan students decreased from Q4 2021 to Q4 2022, from 14.17 minutes to 11.83 minutes. This indicates that engagement decreased for the typical student in this group (i.e., the student in the middle of the distribution). The increase in the mean might be driven by a small number of free-plan students who significantly increased their engagement in Q4 2022, while the majority did not increase their engagement or even reduced it.

* **Standard Deviation:** The standard deviation for the low-engagement-free-plan students increased from 26.23 minutes in Q4 2021 to 468.93 minutes in Q4 2022. This indicates a more significant variability in the minutes watched by these students in Q4 2022 compared to Q4 2021. The behavior of these students then became more diverse in Q4 2022, with some watching a lot of content and others watching very little.

These results suggest a complex picture for the initially low-engagement-free-plan students. While the mean minutes watched increased,signifying an increase in overall engagement, the median minutes watched decreased, indicating that the typical student in this group did not increase their engagement. This discrepancy and the increased standard deviation suggest that a small number of students within this group might significantly increase their engagement while the majority did not. This might imply the need for targeted strategies to boost engagement among the broader population of initially low-engagement-free-plan students.


### **Paid vs Free-Plan Students**

* On average, low-engagement-paid students initially increased their watching time more significantly than the free-plan students from Q4 2021 to Q4 2022. This could suggest that paid-plan students find more value in the platform, possibly due to premium features or content that are available to them. In contrast, the median watch time decreased for free-plan students, suggesting that the typical free-plan student in this group did not increase their engagement. This discrepancy might indicate that the strategies or features designed to increase engagement are more effective for paid-plan students. It could also suggest that the monetary investment leads to increased usage due to a desire to get their money's worth.

Based on the findings, the platform is more successful in increasing engagement among students who make a monetary investment (i.e., paid-plan students). But the increased variability, especially among paid-plan students, indicates that there are likely differences in how individual students are responding to the platform's offerings. Therefore, personalized approaches might be beneficial in boosting engagement, and further analysis could help understand the factors that drive increased engagement among paid- and free-plan students.

## Further Descriptive Statistics on the Difference in Engagement between Paid- and Free-plan Subscribers in Q4 2021 and Q4 2022

For **Paid-plan Students**, the skewness increased from 0.63 in Q4 2021 to 7.07 in Q4 2022.

<div align="center">
<img width="489" alt="Screenshot 2024-06-20 at 12 45 25" src="https://github.com/MichAdebayo/Customer-Engagement-Analysis-with-Excel/assets/92400436/eb58c42c-8923-4138-ac10-952dd3b62a73">
</div>

The skewness for **free-plan students** increased from 1.17 in Q4 2021 to 15.06 in Q4 2022, indicating positive skewness.

<div align="center">
<img width="486" alt="Screenshot 2024-06-20 at 13 00 22" src="https://github.com/MichAdebayo/Customer-Engagement-Analysis-with-Excel/assets/92400436/ddaa1f4a-89b2-4870-98c4-259f991107b7">
</div>

In both cases, the data is positively skewed and this is supported by the fact that the mean is greater than the median in both groups. This increase in skewness suggests that more students watch significantly more content than most over time, thus, pulling the mean upwards. Consequently, the mean is not a good indicator of central tendency as it cannot accurately reflect the typical value of the dataset.

Further, for **Paid-plan Students**, the kurtosis increased from -0.85 in Q4 2021 to 58.48 in Q4 2022, while that of the **Free-plan Students** increased from 0.36 in Q4 2021 to 315.76 in Q4 2022. Kurtosis values greater than 0 indicate that the data has heavier tails and a sharper peak than the normal distribution (leptokurtic). A leptokurtic distribution has a high positive kurtosis, suggesting that it’s very peaked and has a relatively large number of outliers. This type has a higher frequency of extreme values or outliers. The increase in kurtosis over time suggests more extreme cases in the data in Q4 2022 than in Q4 2021, particularly for free-plan students.

Overall, the increasing skewness and kurtosis for both groups from Q4 2021 to Q4 2022 suggest a growing number of students watching significantly more content than the majority. This is especially true for free-plan students with a higher skewness and kurtosis in Q4 2022 than paid-plan students.

## Confidence Intervals for Students' Engagement in Q4 2021 and Q4 2022

### **Paid-plan Students**

<div align="center">
<img width="576" alt="Screenshot 2024-06-20 at 13 17 35" src="https://github.com/MichAdebayo/Customer-Engagement-Analysis-with-Excel/assets/92400436/12b85f7e-2020-44a3-92f7-5dfd3f0d7b81">
</div>

For paid-plan students, there's an increase in engagement from Q4 2021 to Q4 2022. The confidence interval for the average minutes watched by paid-plan students increased from Q4 2021 (316.25 to 348.76 minutes) to Q4 2022 (351.91 to 384.72 minutes). This suggests that we can be 95% confident that the true average minutes watched by all paid-plan students in the population increased from Q4 2021 to Q4 2022.

### **Free-plan Students**

<div align="center">
<img width="608" alt="Screenshot 2024-06-20 at 13 19 39" src="https://github.com/MichAdebayo/Customer-Engagement-Analysis-with-Excel/assets/92400436/4810543c-5cce-41d8-8b21-899127fa633c">
</div>

Among free-plan students, there's a decrease in engagement from Q4 2021 to Q4 2022. The confidence interval for the average minutes watched decreased from Q4 2021 (129.92 to 137.95 minutes) to Q4 2022 (67.71 to 70.59 minutes). We then can be 95% confident that the true average minutes watched by all free-plan students in the population decreased from Q4 2021 to Q4 2022.

### **Comparison between Paid- and Free-Plan Students (Q4 2022)**

* Students with a paid-plan subscription watch substantially more than those without. The confidence interval for the average minutes watched in Q4 2022 was 61.71 to 70.59 minutes for free-plan students and 351.99 to 384.72 minutes for paid-plan students. We then can be 95% confident that paid-plan students watched significantly more minutes than free-plan students in Q4 2022. This aligns with the expectation that paid-plan students who have invested in the platform tend to be more engaged than free-plan users. 

Please note that these are just interpretations based on the confidence intervals. Actual cause-effect relationships must be examined further to understand the causes behind these engagement changes. The fact that paid-plan subscribers watch more doesn't necessarily mean that having a paid-plan subscription encourages them to watch more. For example, the higher engagement among paid-plan students may be due to the additional features or content available or because more engaged students are more likely to choose a paid-plan subscription. Similarly, the decrease in engagement among free-plan students could be due to various factors, such as changes in the platform, competition from other platforms, or changes in the user base.

## Hypothesis Testing of Student Engagement in Q4 2021 vs. Q4 2022

For this analysis, the following hypothesis was made for both paid- and free- plan students: 

* H~0~ : The engagement (minutes watched) in Q4 2021 is higher than or equal to the one in Q4 2022 (μ1 ≥ μ2)

* Assumption: There is an unequal variance between free- and paid- plan students. 

To validate this assumption, a two-sample f-test for variances was performed to prove the assumption of unequal variances between the samples for free- and paid-plan subscribers. 

<div align="center">
<img width="448" alt="Screenshot 2024-06-20 at 13 50 26" src="https://github.com/MichAdebayo/Customer-Engagement-Analysis-with-Excel/assets/92400436/680e67da-19da-4158-9263-715cba71403b">
</div>

The p-value indicates the probability of obtaining the observed f-value if the null hypothesis (equal variances) were true. The sample variances are not identical since the p-value in both cases is 0. Therefore a t-test was carried out. 

### **Paid-plan Students**

<div align="center">
<img width="562" alt="Screenshot 2024-06-20 at 13 39 45" src="https://github.com/MichAdebayo/Customer-Engagement-Analysis-with-Excel/assets/92400436/22a9dbfc-306d-46eb-80e8-9b52158e4e93">
</div>

**Conclusion:** Reject H~0~ because the p-value is lower than the specified significance level α (0.05).

**Summary:** With a t-statistic of -3.05 (less than the critical value of -1.645), the null hypothesis is rejected because the negative t-statistic indicates that  (the mean minutes watched by students in Q4 2021) is significantly smaller than  (the mean minutes watched by students in Q4 2022). Hence, based on the available data, there is enough evidence against the null hypothesis.

### **Free-plan Students**

<div align="center">
<img width="527" alt="Screenshot 2024-06-20 at 14 03 51" src="https://github.com/MichAdebayo/Customer-Engagement-Analysis-with-Excel/assets/92400436/0b32cc60-f917-419a-9920-1a05bea27486">
</div>

**Conclusion:** Fail to Reject H~0~ because the calculated t-statistic is higher than the critical value.

**Summary:** With a t-statistic of 29.78 (greater than the critical value of -1.645), you would fail to reject the null hypothesis. This means there’s not enough evidence to conclude that μ1 is smaller than μ2. So, the data supports the null hypothesis that 
μ1 is larger than or equal to  μ2. These results align with previous findings from the confidence intervals and further underscore the difference in engagement patterns between paid- and free-plan students.

* ### **Which, if committed would result in a higher cost for the company: Type I or Type II error?**

A Type I error (false positive) occurs when you reject the null hypothesis, which is true. In this case (i.e., based on the null hypothesis), this would mean concluding that engagement in 2022 is higher when it's not.  

A Type II error (false negative) occurs when you fail to reject the null hypothesis, but it’s false. In this case, this would mean that the engagement in 2022 is not higher than it is. 

However, results show that the case to either support or reject the null hypothesis is different for paid- and free-plan students. Therefore, the cost to the company of each type of error would depend on the implications of incorrectly concluding that engagement has increased, potentially leading to over-investment in certain features or complacency about needing to improve features **versus** incorrectly concluding that engagement has not increased, potentially missing out on recognizing successful features or identifying areas that need improvement.

## Hypothesis Testing of Free-plan Student Engagement in Q4 2022 (US versus Indian users)

For this analysis, the following hypotheses were made: 

* H~0~ : The engagement (minutes watched) in the US is higher than or equal to that in India (μ1 ≥ μ2).
* H~0~ : The engagement (minutes watched) in the US is lower than that in India (μ1 < μ2).
  
 * Assumption: There is an unequal variance between US and Indian Free-plan subscribers. 

To validate this assumption, a two-sample f-test for variances was performed to prove the assumption of unequal variances between the samples for US and Indian Free-plan subscribers. 

<div align="center">
<img width="593" alt="Screenshot 2024-06-20 at 14 36 15" src="https://github.com/MichAdebayo/Customer-Engagement-Analysis-with-Excel/assets/92400436/f6e14ee8-6e20-480e-b798-c2296f52c1e5">
</div>

The p-value indicates the probability of obtaining the observed f-value if the null hypothesis (equal variances) were true. The sample variances are not identical since the p-value is lower than 0. Therefore a t-test was carried out.   

<div align="center">
<img width="569" alt="Screenshot 2024-06-20 at 14 43 07" src="https://github.com/MichAdebayo/Customer-Engagement-Analysis-with-Excel/assets/92400436/eba5e44d-40ec-43d0-9771-5f0e8925f057">
</div>

**Conclusion:** Fail to Reject H~0~ because the p-value is higher than the specified significance level α (0.05).

If the hypothesis that US students watch more or an equal amount of content as Indian students is rejected, this suggests that US students watch less content on average than students in India.

This could have the following implications.

**Market Differences:** These details might indicate that the platform is more engaging or relevant to students in India than US students. Understanding the reasons behind this could be valuable. Are the platform’s specific features, content, or aspects particularly appealing to Indian students? Such questions need to be addressed further but are beyond the scope of this analysis.

**Growth Opportunities:** If US engagement is lower, this could represent a growth opportunity. The 365 company might seek ways to increase engagement among US students, involving marketing efforts, adding more content relevant to US students, or other strategies.

**Resource Allocation:** This information could be helpful when deciding where to allocate resources. For example, if Indian students are more engaged, investing in more content and features targeted toward this audience might make sense.

## File Information

The Excel file 'Engagement_Project.xlsx' consists of 7 sheets with each sheet containing specific information (or solution) linked to the project's tasks and corresponding data.
