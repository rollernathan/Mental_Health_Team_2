# Mental_Health_Team_2
Project 1 Repo for Team 2


Project participants:

Nishi Thapliyal

Nathan Roller

Stacey Walker

Darell Johnson


# Project Overview

Mental health is an important part of one's overall well being. It is as important as physical health. Many factors can contribute to one's mental health. Going to work is a common activity in many adult lives, which can significantly impact one's mental health. Within a workplace, there are multiple factors that can impact mental health, such as remote work setups, ease of taking leave, mental health programs, etc.

A 2014 survey assess attitudes toward mental health and the frequency of mental health disorders in the workplace. The findings from this survery were analyzed to extract conclusions about what factors can affect mental health treatment seeking behavior.

Survey link: https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey/data 

## Questions to Answer

1. Does remote vs. onsite work affect mental health in the workplace?
2. How does mental health impact work performance?
3. Is there a relationship between the level of difficulty of taking leave and mental health outcomes? 
4. What is the impact of company size on mental health?
5. Are mental health programs implemented by companies effective?
6. Is the number of people seeking treatment randomly distributed?
7. Is there a relationship between age and seeking treatment?
8. Are there differences in mental health treatment seeking behavior between self employed and employed individuals?
9. Is there a relationship between the family history of mental health and the behavior of those seeking mental health treatment?

## Important things to consider

- The dataset was filtered by participants who live in the United States
- For the "self-employed" category, NA values were converted into "No" for ease of analysis


1. Relationship between remote work and mental health in the workplace

![Remote work in the workplace](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/nthapliyal/Figures/remote_status_vs_treatment.png)

The percentage of participants who seek mental health treatment are approximately equal between those who work remotely and those who do not. This suggests that working remotely is not a major factor that affects people mental health treatment or not.

2. Impact of mental health on work performance

![Impact of mental health on work performance](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/nthapliyal/Figures/work_interference_vs_treatment.png)

Of those who do not seek mental health treatment, a majority of participants (approximately 50%) report that their mental health does not interfere with their work. This may be due to either being in good mental health or lack of awareness of how mental health can affect performance at work. Of those who do seek mental health treatment, a majority of participants (approximately 55%) report that their mental health sometimes interferes with their work. This may be explained by the fact that seeking mental health treatment may increase awareness of work can be affected by mental health issues. The next largest groups (each at approximately 20%) each report that their mental health either rarely or often interferes with work. For those who report their mental health rarely affects their work performance, this may be due to the fact that seeking treatment is effective in alleviating work interference. And for those who report that their mental health often interferes with work, that may be the reason in itself for one to seek treatment. 

Question: 
Does the difficulty/ease of taking mental health leave from work affect whether or not employees seek treatment?

![Ease of Taking Leave](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/Project%201_images/P1_Graph_EaseOfLeave.png)

Summary: 
A review of the dataset shows a correlation between the ease of taking mental health leave and whether or not a person gets treatment. As shown in the bar chart, the majority of employees are unsure what their company's mental health leave policy entails. This could be for a variety of reasons, including a lack of need/interest on the part of the employee, or a lack of communication from management. The latter implies that mental health is not at the forefront of the organization, while the former could happen for a variety of reasons. Of the respondents, the ones who answered "Don't Know" are the only group that had less employees taking leave than not.

When considering the difference between the “somewhat easy/difficult” and “very easy/difficult”, we have to consider the subjective nature of the wording. What some people consider "very" difficult, others may consider only "somewhat" difficult. For that reason, it makes sense to review this dataset by looking at “somewhat” and “very” difficult or easy together, which shows that people are much more likely to take leave when the company policy is easy versus when it is difficult. 

Limitations of this dataset:
To understand the reasons people do or do not take leave, we would need to look more deeply into where they live, what their family situation was like and what their position in the company might be. For example, are higher level employees more or less likely to take leave? What role does income play? Does the company offer insurance that covers mental healthcare or do they just have a leave policy? 

Though many of the datapoints are still relative today, mental health is a rapidly evolving field, but remains relatively new in terms of being something that is dealt with in the workplace. In recent years, particularly since the pandemic, work situations have changed dramatically, so some of the responses in this dataset could be outdated. For example, many more people work from home or have a hybrid arrangement than they did in 2014 when this was conducted. It is also true that more companies than ever have implemented mental health policies since 2014. 

Question:
Does company size impact whether or not an employee seeks mental health treatment? 

![Company Size and Mental Health Treatment](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/Project%201_images/P1_Graph_Company_Size.png)

Summary:
Employees are willing to seek mental health treatment regardless of the size of the company, with the exception of companies that have 1000+ employees, which had an even number people who answered "yes" and "no" to seeking mental health treatment.

People working for smaller companies had more willingness to seek treatment, which could be for a variety of reasons, such as the means of communication and closeness of the relationships between the employer and staff.

In addition to the graph, the boxplot shows that more employees sought treatment overall than those who did not. 

![Boxplot Overall Sought Treatment](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/Project%201_images/Box%20plot.png)

Limitations:
Companies with 500-1000 employees are underrepresented in this dataset. Despite the underrepresentation, however, the results follow the same trend as the other populations.

Additionally, the data does not offer much information about the company other than size, so there are many unknowns about the workplaces. 

Overview
This project aims to analyze the relationship between family history of mental health issues, employment status, and the likelihood of seeking mental health treatment. The analysis employs various statistical tests and visualizations to identify patterns and significant factors.
Analysis Summary
Objectives
1.	Primary Hypothesis 1: Self-employed individuals are less likely to seek mental health treatment compared to employed individuals.
2.	Primary Hypothesis 2: Individuals with a family history of mental health issues are more likely to seek mental health treatment compared to those without such a history.
Findings
1.	Employment Status:
o	The analysis shows no substantial difference in mental health treatment-seeking behavior between self-employed and employed individuals.
o	Bar Graph: The number of self-employed individuals seeking treatment is slightly higher than those not seeking treatment. For employed individuals, the numbers are almost equal.
![Employment](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/djohnson/Images/Treatment%20Vs%20Employment%20Bar.png)
2.	Family History:
o	Individuals with a family history of mental health issues are significantly more likely to seek treatment compared to those without such a history.
o	Bar Graph: Individuals with a family history seeking treatment significantly outnumber those not seeking treatment, and the opposite is true for individuals without a family history.
![Family Bar](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/djohnson/Images/Family%20History%20vs%20Seeking%20Treatment%20Bar.png)
o	Heat Map: Supports the finding that family history influences treatment-seeking behavior.
![Family Heat Map](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/djohnson/Images/HeatMap.png)
o	Violin Plot: Shows a higher density of treatment-seeking behavior among individuals with a family history.
![Family Violin](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/djohnson/Images/Family%20History%20vs%20Seeking%20Treatment%20Violin.png)
Statistical Analysis
•	T-test:
o	T-statistic: 14.755
o	P-value: 3.919e-45
Conclusion
•	Family history significantly influences the likelihood of seeking mental health treatment, whereas employment status does not appear to be a strong determinant.
•	These insights can guide further research and targeted interventions in mental health services, emphasizing the importance of family history in shaping treatment-seeking behavior.
This project provides a comprehensive analysis of the factors influencing mental health treatment-seeking behavior, with a focus on family history and employment status. 


