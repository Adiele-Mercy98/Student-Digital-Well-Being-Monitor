# Student-Digital-Well-Being-Monitor
The analysis provides Student social media usage containing multiple variables across independent categories (Age, Gender, Academic-level, Country, Average-daily-usage-hours, Most-used-platform, Relationship-status, Conflicts-over-social-media, Addicted-score) and dependent variables(Affects-academic-performance, Sleep-hours-per-nights, Mental-health-score). 
<img width="2471" height="1216" alt="Student Digital Well-Being Monitor" src="https://github.com/user-attachments/assets/676ff94f-ac0b-4409-b78f-7bf264016f69" />
Introduction
The primary objective is to analyze a dataset of 705 student responses to understand the relationship between social media usage, academic life, sleep patterns, mental health, and other key demographic factors.

Problem Being Addressed
The analysis seeks to answer:
•	How does social media use impact the academic performance, mental health, and sleep of students?
•	what are the key correlating factors in their demographics and usage habits?

Datasets and Methodologies
Dataset: The analysis provides Student social media usage containing multiple variables across independent categories (Age, Gender, Academic-level, Country, Average-daily-usage-hours, Most-used-platform, Relationship-status, Conflicts-over-social-media, Addicted-score) and dependent variables (Affects-academic-performance, Sleep-hours-per-nights, Mental-health-score).
Methodologies: The primary methodology involves aggregation and counting using Pivot Tables in Excel to analyze relationships, such as the total Mental Health Score (MHS) across various categories (e.g., Academic Level, Most Used Platform). Summation of the Mental Health Score and Sleep Hours Per Night acts as proxies for overall well-being.
Data Story
This dataset examines the impact of social media on students' study, considering their mental health. it includes responses from 705 students’ countries. This dataset tells how much students use social media daily and whether if affects their academic performance. 
Data Source
The data is a survey-based dataset collected from students across various educational levels and countries.
Data Collection Process
Data was gathered via a survey, with 705 distinct student responses recorded, likely involving self-reported metrics (e.g., usage hours, sleep hours, score).
Data Structure
The dataset contains 705 rows and 13 columns, where each row represents a single student's response. Key variables include:
•	Demographics: Age, Gender, Academic_Level, Country, Relationship_Status.
•	 Usage Metrics: Avg_Daily_Usage_Hours, Most_Used_Platform, Addicted_Score.
•	 Impact Metrics: Affects_Academic_Performance, Sleep_Hours_Per_Night, Mental_Health_Score, Conflicts_Over_Social_Media.

Important Features and Their Significance
•	Academic_Level: Essential for segmenting students and identifying how effects vary by educational stage (Undergraduate is the largest group, 353 total).
•	Mental_Health_Score: The primary dependent variable for well-being analysis (Total Score: 4,390).
•	Avg_Daily_Usage_Hours and Addicted_Score: Key independent variables for understanding the depth of social media engagement.

Data Limitations or Biases
The primary limitation is the self-reported nature of the numerical data (e.g., usage hours, sleep hours, mental health score), which is subject to recall bias. Also, the student distribution skews heavily toward Undergraduates and early ages (19-21), potentially skewing the findings away from the high school or older graduate population.
Data Splitting
The analysis separated independent variables from dependent variables. This separation enabled correlation analysis and causal relationship exploration between operational factors and performance outcomes.
Industry Context
Educational Administrators, Student Counseling Services, University Wellness Departments, and Academic Researchers.
Value to the Industry
The insights can guide university policy on screen time and technology use, inform counseling interventions, and help design academic support programs to mitigate the negative consequences of excessive social media use.
Pre-Analysis
Project Split
Category One: Independent Values
•	Age
•	Gender
•	Academic-level
•	Country
•	Average-daily-usage-hours
•	Most-used-platform
•	Relationship-status
•	Conflicts-over-social-media
•	Addicted-score
Category Two: Dependent Values
•	Affects-academic-performance
•	Sleep-hours-per-nights
•	Mental-health-score

Potential Analysis/Questions
•	Academic performance analysis by Age
•	Academic performance analysis by relationship status
•	Academic performance analysis by academic-level
•	Mental-health-score analysis by gender
•	Mental-health-score analysis by Academic-level
•	Mental-health-score analysis by Addicted-score
•	Mental-health-score analysis by most-used-platform
•	Sleep-hours-per-night analysis by relationship-status
•	Sleep-hours-per-night analysis by conflicts-over-social-media
•	Sleep-hours-per-night-analysis by Academic level

Potential Insights
•	Understand how age influences the academic impact of social media use
•	Explore whether relationship involvement affects focus and academic impacts.
•	Examine if educational stage affects vulnerability to social media distraction
•	Compare stress or anxiety differences between male and female students.
•	Assess if academic pressure and social media stress differ by level.
•	Analyze whether high social media addiction predicts poor mental health
•	Identify which platform is linked to poorer mental health outcomes.
•	Assess whether relationship status affects sleep time due to online activity
•	Investigate whether social media arguments disturb sleep quality
•	Determine if academic workload or level impacts sleep loss from social media


In Analysis
Academic Performance Analysis by Age Group
Observations:
•	Age group 18 records the lowest interference rate, with approximately 68% of students reporting that social media does not affect their academic performance.
•	Age group 19 surge in negative impact occurs here with "yes" percentage rising sharply to approximately 45%. This represents the first major drop in academic safety from the previous year
•	Age group 20, the percentage of students reporting a negative impact peaks exactly at 50% marking this age as the highest-risk bracket in the dataset for self-reported academic interference
•	Age group 21 to 24 reported academic interference begins a noticeable steady decline across the older age range. The proportion reporting "No" impact gradually increases.
Pre Insights:
•	For age group 18, this suggests a low-risk baseline, students at this age often New entrants either possess better initial digital discipline or are engaged in foundational coursework that has not yet created severe conflicts with their social media habits.
•	For age group 19, this jump signals a critical transition point. As students progress to the second year, the increased academic rigor and complexity of coursework begin to clash directly with established social media consumption patterns, leading to greater self-reported interference.
•	for Age group 20, often coincides with the high-stakes middle phase of undergraduate education. The combination of peak academic demand and entrenched digital habits creates the most severe conflict, resulting in maximum perceived academic disruption.
•	for Age group 21+, this points to maturation and adaptation. Older students are likely to have either developed superior self-regulation skills, adapted their habits to prioritize their goals, or self-selected into advanced academic tracks that require a higher level of digital discipline.

Academic Performance Analysis by Academic-Level
Observations:
•	The undergraduate level has the highest count of records (353), representing the largest portion of the sample analyzed 50.1%
•	The Graduate level has the second-highest count (325) very close to the undergraduate count (46.1%)
•	The High School level has the lowest count (27) by a large margin, making up a very small fraction (3.8%).
Pre Insights:
•	The undergraduate group constitutes the statistical majority of the students whose academic performance data was captured. Due to its size, the undergraduate level will disproportionately influence the overall academic performance averages and is the most important segment to target for broad-based academic support programs.
•	for Graduate, the sample is nearly evenly split between undergraduate and graduate students. This suggests that any subsequent analysis of actual performance, must carefully account for the differences in academic rigor and standards inherent to the two levels. Comparing raw performance scores directly without normalization might be misleading.
•	For High School, the sample size means that any conclusions drawn about the actual academic performance of the High School group will have low statistical power and should be interpreted with extreme caution. This group may represent high school students who are part of a specific preparatory or dual-enrollment program being tracked.

Academic Performance Analysis by Relationship-status
 Observations:
•	The single status group has the highest count of records (364).
•	The In a relationship group has the second -highest count (289).
•	The complicated status group has the lowest count (52).
Pre Insights:
•	The single group forms the statistical majority of students whose academic performance data was collected. While the high count doesn't imply better performance, its size makes it a critical segment for any general academic policy or intervention.
•	The In-a-relationship group is significantly large, though smaller than the single group. Any difference in their actual academic performance compared to the single group would be a meaningful finding, suggesting a potential correlation between relationship commitment and study habits/time allocation.
•	The complicated group is the smallest group, which means any analysis of their actual performance would need to be treated with caution due to the small sample size. If their performance is shown to be significantly different (higher or lower) in a subsequent analysis, it could indicate that the emotional or time demands associated with a "complicated" status may have a disproportionate impact on academic focus.

Mental-Health-Score by Academic-Level 
Observations:
•	The Undergraduate level has the highest aggregated mental-health-score (2181)
•	The Graduate level has a high aggregated mental-health-score (2071)
•	The High School level has a significantly lower aggregated mental-health-score (138)
Pre Insights:
•	for undergraduate level, assuming a higher score indicates a greater total mental health need or challenge, this group represents the single largest area of mental health concern in the aggregate.
•	for Graduate, this indicates that the cumulative mental health burden among graduate students is nearly as high as that of undergraduates. Graduate students face different stressors, such as thesis requirements, higher academic specialization, balancing research/ teaching with course works, and often financial pressures. This proximity of scores suggests that mental health resources cannot neglect the graduate population, as their needs are substantial.
•	for High School, this low sum is overwhelmingly a consequence of the very small sample size.

Mental-health-score by Top 5 most-used-platform 
Observations:
•	The platform most associated with the highest aggregated mental-health-score is Instagram (1525), leading by a significant margin.
•	TikTok is the second-highest platform with a score of 880
•	The score of Facebooks 826
•	The score of WhatsApp has a dramatically lower score 299 compared to the top three platforms
•	Twitter now X has the lowest aggregated mental-health-score (205) among the top five
Pre Insights:
•	For Instagram, the high sum suggests that students who identify Instagram as their most used platform face the greatest collective mental health burden. This may be linked to the platform's emphasis on visual perfection, self-comparison, and curated lifestyles, which are often cited in research as contributors to anxiety and lower self-esteem.
•	For TikTok, while significantly lower than Instagram, the score remains high. This may be related to the platform's addictive, scroll-based nature, which can lead to time displacement (taking time away from sleep or study) and shortened attention spans, indirectly impacting mental well-being and academic focus.
•	Given that Facebook often caters to broader social networks (including family and older connections), it's associated mental health score might stem from issues related to privacy, maintaining a digital reputation or the stress of navigating complex, diverse social circles.
•	WhatsApp is primarily a direct messaging/utility tool rather than a content consumption platform focused on public performance. The lower score suggests that platform usage centered on direct, private communication may have a significantly milder correlation with severe mental health challenges
•	X similar to WhatsApp, this low score suggests that platforms primarily focused on text, news consumption, and brief public discourse may be less correlated with the highest mental health scores compared to visually-driven, performance-based platforms like Instagram.

Sleep-hours-per-nights by Relationship-status 
Observations:
•	Students who identify as Single report the highest average sleep duration at approximately 7.1 hours per night.
•	Students who are In a Relationship report a notably lower average sleep duration, dropping to approximately 6.4 hours per night
•	Students reporting a Complicated relationship status report and average sleep duration of approximately 6.6 hours per night. This places them slightly better off than those In Relationship but still significantly lower than single students.
Pre Insights:
•	Single students typically have fewer external time commitments and less social obligation tied to another person's schedule (e.g., late-night calls, planning dates). This grants them greater autonomy and flexibility in their schedule, allowing them to prioritize and maintain a healthier sleep routine.
•	Being in a relationship introduces social time conflicts (e.g., spending time with a partner, late-night communication) that often directly infringe on the sleep window. The pressure to maintain the relationship and balance it with academic demands results in this group experiencing the greatest measurable loss of sleep.
•	The sleep duration here suggests a blend of factors. While there may be fewer consistent late-night obligations than a steady relationship, the emotional stress and uncertainty inherent in a "complicated" status likely contribute to sleep latency and poorer sleep quality, resulting in a duration lower than the single group

Mental health score by Gender
Observations:
•	Average mental health score for female students is visibly lower than  that of male students 
•	The average Mental health score for male students is higher than the female average.
Pre Insights:
•	Female students appear more acutely vulnerable to the stressors of social media use and academic life, which can significantly impact their mental well-being. This suggests a potential requirement for targeted support programs designed to address known stressors such as comparison culture, body image issues, and the emotional toll of online conflicts, which often disproportionately affect this demographic.
•	While the average is higher, the presence of scores in the lower range confirms vulnerability exists. Their overall higher scores may partly be due to different coping mechanisms or a reluctance to fully disclose mental health challenges. Interventions for male students should focus on promoting open communication, recognizing subtle signs of distress, and utilizing less conventional support avenues.

Sleep-hours-per-nights by Academic-Level 
Observations:
•	High School students report the lowest average sleep hours in the dataset at approximately 6.3hours per night.
•	Undergraduate students report a slightly higher average sleep duration of approximately 6.8 hours per night.
•	Graduate students report the highest average sleep hours at approximately 7.2 hours per night.
Pre Insights:
•	High School: This severe sleep deficit suggests a profound impact from a combination of factors common in this level: early school start times, a heavy homework load, and difficulty enforcing digital boundaries at home. High School students are the most chronically sleep-deprived group, signaling a serious concern for their cognitive development and performance.
•	Undergraduate: The increased freedom and flexibility of the university schedule likely allows for a slight improvement over the rigid high school structure. However, this deficit suggests that the demands of university life, combined with independent social schedules and digital consumption, still consistently erode the necessary time for restorative sleep.
•	Graduate: This improved sleep duration is likely due to increased maturity, stronger self-regulation, and often more flexible schedules that allow for better pacing of work. This group may prioritize sleep more effectively, viewing it as crucial for high-level cognitive performance, indicating that discipline increases with academic progression.

Data Visualizations and Charts
Sleep-Hour-Per-Night by Relationship-Status
<img width="2177" height="958" alt="Student Dig  Sleep hr by Relshp" src="https://github.com/user-attachments/assets/b258e6b5-7c1d-4053-84c7-519eb6bcfa1a" />

 
This doughnut chart displays the aggregated total sleep hours per night for three relationship status groups. The Single relationship status group has the highest aggregate total sleep hours at 2679.9. This represents the largest segment of the doughnut chart, The In Relationship status group is the second largest contributor with 1973.9 total sleep hours, The Complicated status group contributes the least to the total, with only 188.4 sleep hours.

 
The doughnut chart visually confirms the near-even split, with the segment for Male (dark blue) 2210 being only marginally larger than the segment for Female (light gray/blue) 2180.

Academic Performance Analysis by Age
<img width="2410" height="1017" alt="Student Dig  Aca Perf  by Age" src="https://github.com/user-attachments/assets/7b413282-4351-4a41-8dc5-4082d7212950" />

 
The Bar chart titled Academic Performance Analysis by Age displays the counts of affects within the various age groups with Age 20 leading the chart with the highest count 165, Age 19 follows closely behind with a count of 163, Age 21 has the third highest count at 156, Age 22 has a count of 147, Age 23 shows a dramatic decrease in the count dropping to 34, Age 24 continues this sharp decline with a count of 26, and Age 18 has the lowest count displayed on the chart at just 14.

The data shows a very high concentration of academic performance records in the traditional university age range (19-22), accounting for the vast majority of the total count (631 out of 705). There is a sharp and sudden drop-off in representation for both the older (23 and 24) and younger (18) age groups, suggesting that the population being studied is heavily skewed towards students in their late teens and early twenties.

Academic Performance Analysis by Academic-Level
 <img width="2387" height="1034" alt="Student dIG  Aca  Perf  by Aca Level" src="https://github.com/user-attachments/assets/aa378001-8c61-40fe-9d53-145b2e8f956f" />

The Bar chart shows the distribution of records across three academic levels with Undergraduate academic level leading the chart with the highest count of records at 353, The Graduate academic level is very close second with a count of 325, Teh High School level has a significantly low count of 27, which is over ten times less than the other two categories.

The dataset is nearly equally split between the Undergraduate (50.1%) and Graduate (46.1%) academic levels, while the High School level is negligibly represented (3.8%). This indicates the analysis is overwhelmingly focused on the university student population.


Academic Performance Analysis by Relationship-Status 
<img width="2433" height="989" alt="Student Dig  Aca  Perf  by Relshp" src="https://github.com/user-attachments/assets/e1780b98-bc7b-4632-b204-f42fd2d04ea8" />

The bar chart shows the count of Affects-Academic-Performance by relationship status with the Single relationship status leading at 384, representing more than half of the total records, The In Relationship status is the second largest group with a count of 289, The Complicated status has the lowest representation with only 32 records.
The analysis is primarily weighted towards individuals who are Single or In a Relationship, which together account for 95.4% of the entire dataset, rendering the Complicated status minimally represented.

Mental-Health-Score by Academic-Level
<img width="2306" height="1008" alt="Student Dig  Mental Health by Aca Level" src="https://github.com/user-attachments/assets/8d96ab16-37c2-4467-b87c-a8362951d47b" />

 This bar chart displays the aggregated mental-health-score for three academic levels. The Undergraduate academic level has the highest total Mental health score at 2181, the Graduate academic level is very close to the leader, with a total score of 2071, and the high school level has a significantly low total score of 138.
The chart visually confirms the close relationship between the Undergraduate and Graduate scores, with the High School bar being almost invisible by comparison.


Mental-Health-Score by Addicted Score
 
This bar chart displays the aggregated mental health score for various levels of "Addicted score". The highest Mental Health Score is associated with an Addicted Score of 7 at 1227, The next two highest scores are Score 5 at 961 and Score 8 at 743, Following the top three, the scores decline somewhat consistently score 4: 661, score 6: 414, score 9: 247,The lowest scores, Score 3 and Score 2, contribute minimally, with 128 and 9 respectively.





Mental-Health-Score by Top 5 Most-Used-Platform
 <img width="2171" height="1022" alt="Student Dig  Mental Health by top 5 pf" src="https://github.com/user-attachments/assets/12d9d96f-6c71-4377-9a17-f51e847e8177" />

This chart displays the sum of Mental health score aggregated by the five most-used social media platforms. Instagram leads the chart with the hi total Mental health score by a large margin at 1525, TikTok is the second with a score of 880 and Facebooks very close behind at 826, WhatsApp and Twitter make ul the lowest tier with scores of 299 and 205, respectively.


Sleep-Hour-Per-Night by Academic-Level

 This doughnut chart displays the aggregated total sleep hours per night for three academic levels. The Undergraduate academic level has the highest aggregate total sleep hours at 2410.5. This is the largest segment of the doughnut chart, The Graduate academic level is a very close second with 2284.8 total sleep hours, The High School level contributes the least to the total, with only 147.3 sleep hours.

Observations and Recommendations

Observations
•	The negative influence of social media on academic performance is not constant but follows a distinct inverted U-cure pattern, with the peak vulnerability concentrated sharply in the mid-stage of the university career (age 20).
•	The dataset is overwhelmingly focused on post-secondary education, with the undergraduate and graduate levels collectively accounting for over 96% of the records. This confirms the analysis is primarily relevant to higher education demographic.
•	The vast majority of the aggregated mental health score (over 96%) originates from the Undergraduate and Graduate populations. While their scores are close, the Undergraduate group contributes the highest single sum, confirming that mental health support is primarily a post-secondary institution challenge in this analysis.
•	There is a clear and steep correlation between the type of social media platform and the aggregated mental health score. Platforms driven by visual content and self-presentation (Instagram, TikTok) correlate with the highest collective mental health burden, while platforms focused on private utility or text-based discourse (WhatsApp, Twitter) correlate with the lowest burden
•	There is a clear and pronounced disparity in mental health outcomes, with the female student population consistently demonstrating lower average Mental Health Scores and a higher density of students in the high-risk category compared to their male counterparts. This disparity identifies female students as the primary demographic requiring urgent and focused mental health intervention.
•	Students in a Relationship report the lowest average sleep hours (\sim 6.4 hours/night), identifying this demographic as the most sleep-deprived and highest risk for fatigue and cognitive decline. The need to balance relationship demands with academic responsibilities appears to be the primary factor eroding the necessary 7+ hours of sleep.
•	There is a distinct positive correlation between academic progression and sleep health. The most critical vulnerability exists at the foundational level, with High School students reporting the lowest sleep hours (\sim 6.3 hours/night). This demonstrates that the severe sleep debt is concentrated at the beginning of the academic journey, placing this group at the highest risk for compromised learning.

Recommendations

•	Stakeholders should implement highly targeted, specialized digital wellness and time management workshops for the student cohort ages 19 to 20. Interventions must move beyond general advice to focus on advanced self-regulation and prioritization techniques designed to mitigate distraction during this specific, high-stakes academic window.
•	The stakeholders should establish a two-tier reporting standard, one focused on the Undergraduate population and the one on the Graduate population, to ensure that academic policies and resource allocation are appropriately tailored to the distinct needs, expectations, and challenges of students at each level. The High School group should be monitored but excluded from major statistical comparisons due to sample size.
•	The Stakeholders should Conduct a deep-dive analysis into the average mental health score per student for both Undergraduate and Graduate levels. If the average scores are comparable, a unified, high-capacity mental health center is warranted. If the averages differ significantly, resources must be split to offer specialized interventions (e.g., career anxiety and financial planning for Graduates; social integration and transitional support for Undergraduates).
•	Stakeholders should develop platform-specific digital well-being campaigns and resource guides targeting the high-risk platforms, especially Instagram.Actionable Step: Launch a targeted psycho-educational module focused on the concept of "Curated Reality" and "Social Comparison Bias" specifically for users of Instagram. This module should provide students with concrete strategies for limiting passive scrolling, improving media literacy regarding visual content, and setting boundaries for self-presentation online
•	Immediately allocate prioritized funding toward establishing gender-targeted mental health resources and digital wellness workshops. These initiatives should include confidential counseling pathways and dedicated peer-support groups designed specifically to address the unique pressures (e.g., social media-induced stress, conflict resolution) contributing to the decline in mental health among female students.
•	The stakeholders should Launch targeted stress and time management workshops specifically for students in relationships. These programs should not only cover academic scheduling but also provide actionable strategies for setting digital and relationship boundaries (e.g., designating "no-phone zones," establishing a late-night communication cut-off) to protect the sleep window and mitigate the documented relationship-based sleep debt. 
•	Prioritize and implement sleep and digital boundary education programs for High School students. These programs should involve parental outreach and focus on setting specific technology curfews (e.g., 9:30 PM), advocating for later school start times, and equipping students with the tools to manage screen time before their poor habits become entrenched in later academic levels.

Unexpected Outcomes
The finding that Graduate students have a slightly higher average MHS and better sleep than Undergraduates is unexpected, as graduate-level studies are often associated with higher stress. This suggests that by the graduate level, students have either self-selected out of the study’s negative impact factors or developed superior mechanisms for managing social media use alongside demanding academic schedules.
Conclusion
The analysis successfully quantified the differential impact of social media use, revealing that High School students are the most negatively affected group in terms of sleep and mental health. Graduate students show the most resilience. Additionally, while relationships correlate with slightly better mental health, they are also associated with less sleep.
Limitation
The analysis could not fully assess the bidirectional relationship between social media use and its effects (e.g., does poor mental health lead to more social media use, or vice-versa?).
Future Research
•	Conduct regression analysis to determine the quantitative impact of Avg_Daily_Usage_Hours and Addicted_Score on Mental_Health_Score and Sleep_Hours_Per_Night.
•	Track a cohort of High School students through to their undergraduate years to monitor how the factors evolve over time.
References
Analytical Tools
•	Microsoft Excel
