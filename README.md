# Customer-Engagement-Analysis-with-Excel

The project aims at analyzing some customer engagement metrics for 365 Company to determine whether the addition of new features increased student engagement.

## Case Description

In 2022, there were high expectations for the growth of the 365 company and increased student engagement based on the introduction of new website platform features. Some of these features included an XP system that enabled students to track their progress, level up, and earn rewards by completing various learning objectives. The platform also offered in-app coins that could be exchanged for special awards, a leaderboard where students could compete for top positions in different divisions, earning weekly rewards and advancing up the ladder, and streaks to motivate students to maintain consistent learning habits. Additionally, the company expanded its course library, covering a broader range of topics to provide its students with a richer set of skills and attract a larger audience. These enhancements were anticipated to positively impact the student experience, create an effective strategy for customer engagement, and contribute to the company's success in the coming year. With this Customer Engagement Analysis Excel project, I analyze whether the new additions to the platform have increased student engagement.

## Dataset

The dataset for this project comes from the 365 company, hence, it is a real-world dataset that represent the company’s operations. Note that personal user information has been masked to ensure privacy. The following are the column values available in the data: 

* **student_id –** the unique identifier for each student in the dataset. The field contains IDs for students who used the 365 Data Science platform with free or paid accounts in **Q4 2021** (October 1, 2021 – December 31, 2021, both included) and **Q4 2022** (October 1, 2022 – December 31, 2022, both included).

* **student_country –** identifies the country of each student. The field provides information about students’ geographic location and can help analyze regional differences or conduct country-specific analyses.

* **minutes_watched_21 –** represents the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2021.
  
* **minutes_watched_22 –** denotes the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2022.

* **Paid –** indicates whether a student had a paid account during the specified period. It is a binary variable, where '1' represents a paid account and '0' represents a free or unpaid account. It helps differentiate between students who have access to additional features or content through a paid subscription.

## Tasks

#### **Task 1:** Compute the mean, median, and standard deviation for paid-plan and free-plan student groups. Is there a difference in engagement between paid- and free-plan subscribers?

Results and Interpretation: 

<div align="center">
<img width="500" alt="Screenshot 2024-06-19 at 16 21 04" src="https://github.com/MichAdebayo/Customer-Engagement-Analysis-with-Excel/assets/92400436/caffa178-890a-4b5f-a55f-9f7f3b858e27">
</div>

**Paid-plan Students**

* **Mean:** Among students who watched between 1 and 100 minutes in 2021, the average minutes watched by paid-plan students increased significantly from Q4 2021 to Q4 2022, from approximately 33.80 minutes to about 273.02 minutes. This suggests a substantial increase in engagement among this group of initially low-engagement-paid-plan students.

* **Median:** The median minutes these low-engagement-paid-plan students watched increased from Q4 2021 to Q4 2022, from 26.33 minutes to 40.28 minutes. While this increase is not as dramatic as the increase in the mean, it indicates that the typical student in this group (i.e., the student in the middle of the distribution) also increased their engagement. This suggests that the increase in engagement was more widespread among paid-plan students and not solely driven by a few outliers.

* **Standard Deviation:** The standard deviation for these low-engagement-paid-plan students increased substantially from 28.21 minutes in Q4 2021 to 854.58 minutes in Q4 2022. This indicates a much larger variability in the minutes watched by these students in Q4 2022 compared to Q4 2021. This could be due to a broader range of engagement levels among the students in Q4 2022, with some students watching very little content and others watching a lot of content.

These results suggest that paid-plan students who were initially low-engagement in 2021 significantly increased their engagement in 2022. But the increased standard deviation indicates a broader range of engagement levels among these students in 2022. Understanding the reasons behind this variability could provide valuable insights for further boosting engagement. For instance, the factors that motivated the students who significantly increased their engagement might be leveraged to encourage increased engagement among other students.


## File Information

The Excel file 'Engagement Project.xlsx' consists of four sheets: Task 1 and 2, Task 3, Task 4, and Task 5. Each sheet contains specific information regarding the project's tasks and corresponding data.
