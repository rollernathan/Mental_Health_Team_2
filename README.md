# Mental_Health_Team_2
Project 1 Repo for Team 2

## Are mental health programs implemented by companies effective at helping employees?

We explored employees who were seeking treatment compared to employees who work for an employer who provides mental health benefits. The bar chart below shows the number of employees seeking treatment (indicated in blue) and the number of employees not seeking treatment (indicated in orange). Across the x-axis, you can see the responses for whether or not the company offers mental health benefits (or the employee doesn't know). The bar chart does indicate more people seeking treatment when the company offers mental health benefits compared to when the company does not offer mental health benefits. For that reason, we believe the mental health programs implemented by companies are effective at helping employees.

![Benefits_Treatment](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/nroller/Images/Benefits_Treatment.png)

While this data was not available in this particular survey, additional analysis can be performed exploring whether or not people were receiving treatment prior to being employed at their company or chose to seek treatment after starting employment at the specific company. 


## Is the number of people seeking treatment randomly distributed?

We investigated the number of people receiving treatment to determine if that number was randomly distributed (expect the same number of people to be seeking treatment as are not seeking treatment). Our null hypothesis is no statistical significance exists in the distribution of people seeking treatment and not seeking treatment.

![Treatment_Expected](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/nroller/Images/Treatment_Expected.png)

We performed a chi-squared test on the data using equal expected amounts for yes and no. The results of the test are included in the table below.

![Benefits_Treatment_Chi_Square_values](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/nroller/Images/Benefits_Treatment_Chi_Square_values.png)

As shown in the table, since the chi square value of 6.34 exceeds the critical value of 3.84, we conclude that the results are statistically significant. This means that with 95% confidence, we can **REJECT** the null hypothesis meaning the number of people who seek treatment in this study is not randomly distributed.

## Is there a relationship between age and seeking treatment or age and knowing if the company offers benefits?

We examined the relationship between age and employees seeking treatment. Our null hypothesis is there is no significant association between age and seeking treatment for mental health. We identified the percentage of the total number of participants in the survey which fall into each age group. Then, we calculated that percentage of the individuals who are seeking treatment (410 total) to achieve the number we would expect to be receiving treatment from that age group as indicated in the Expected Receiving Treatment column in the table below.

![Age_Expected_Treatment](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/nroller/Images/Age_Expected_Treatment.png)

We performed a chi-squared test on the data using the Expected Receiving Treatment column in the table above. The results of the test are included in the table below.

![Age_Treatment_Chi_Square_values](https://github.com/rollernathan/Mental_Health_Team_2/blob/main/nroller/Images/Age_Treatment_Chi_Square_values.png)

As shown in the table, since the chi square value of 0.72 does not exceed the critical value of 9.49, we conclude that the results are NOT statistically significant. This means that with 95% confidence, we can **NOT** reject the null hypothesis meaning there is no significant association between an employee's age and the employee seeking treatment for mental health.
