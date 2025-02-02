# Suicide-Rate-Analysis-An-R-Hackathon-Project

## 📌 Problem Statement

Suicide is a critical global health issue that affects millions of people across different age groups and demographics. Our objective in this hackathon was to analyze global suicide trends using real-world data, explore patterns over time, identify key risk factors, and provide data-driven insights that can help in awareness and prevention strategies.

## 🎯 Objectives of the Analysis

✅ Explore the trends in suicide rates across different regions and demographics.

✅ Analyze the impact of economic indicators (GDP, unemployment, etc.) on suicide rates.

✅ Identify age and gender disparities in suicide rates.

✅ Visualize global suicide patterns using ggplot2.

✅ Provide data-backed insights to inform mental health policies.

## 🔍 Data Sources

The dataset used in this analysis includes:

1. 📊 World Bank & WHO datasets for global suicide rates.
2. 📉 Economic indicators such as GDP per capita, unemployment rate, and inflation.
3. 👨‍👩‍👧 Demographic breakdowns by age, gender, and country.

## ⚙ Methods & Techniques Used

### 🛠 Data Wrangling:

1. Used dplyr to clean, transform, and aggregate suicide data.
2. Merged economic indicators with suicide rate data for correlation analysis.

### 📊 Data Visualization (ggplot2):

1. Time series analysis to observe trends in suicide rates.
2. Heatmaps to show suicide rates by country.
3. Bar charts & boxplots to compare suicide rates across demographics.

### 📈 Statistical Insights & Trends:

1. Correlation analysis between GDP, unemployment rates, and suicide rates.
2. Identified vulnerable age groups based on historical patterns.

## 🌎 Key Insights from the Analysis

🔹 Countries with higher GDP per capita tend to have lower suicide rates, but there are exceptions.

🔹 Unemployment positively correlates with suicide rates, especially in certain age groups.

🔹 Men are more likely to commit suicide compared to women in most regions.

🔹 Suicide rates among the elderly population are higher in some developed countries.

🔹 Certain countries in Eastern Europe & Asia have alarmingly high suicide rates.

## 📊 Visualizations & Findings

### Section 1: Demographic Analysis Visualizations

<img width="753" alt="Screenshot 2025-02-02 at 12 04 11 PM" src="https://github.com/user-attachments/assets/8c875fe5-00e9-4587-a887-bd98652214e0" />

In 1999 and 2003, the highest number of suicides were recorded, with a total count of 256119 and 256079, respectively. The number of suicides increased every year from 1985 to 1996 and again from 1997, with a brief decrease in 1997. Further analysis is needed to understand the gender breakdown of these suicide cases.

<img width="753" alt="Screenshot 2025-02-02 at 12 04 36 PM" src="https://github.com/user-attachments/assets/d03a7b73-e13d-4baf-8d0d-df8af5904fa6" />

The highest rate of suicides appears to occur in the age group of 35-54 years.

<img width="889" alt="Screenshot 2025-02-02 at 12 05 17 PM" src="https://github.com/user-attachments/assets/08ded3e6-2a93-438c-b907-6cf51dbb5760" />
<img width="683" alt="Screenshot 2025-02-02 at 12 05 34 PM" src="https://github.com/user-attachments/assets/0982c1a7-d36e-4978-b3bb-f1e04e508f5e" />

Regardless of the year, the data shows that male suicides are approximately three times higher than female suicides. Furthermore, the suicide rate rises with age, indicating that age is a significant factor in determining suicide risk. This highlights the importance of targeted interventions to address the unique challenges that different demographic groups face, particularly older men who are at the highest risk of suicide. Understanding the relationship between gender, age, and suicide rate can aid in the development of effective prevention strategies and aid in the reduction of suicides.

<img width="919" alt="Screenshot 2025-02-02 at 12 06 01 PM" src="https://github.com/user-attachments/assets/bea87b3f-10c7-444d-887a-d53e1058f08c" />

The trend in suicides in the United States reveals a persistent upward trajectory over the years and a correlation with age, with higher rates of suicide as age increases.

<img width="754" alt="Screenshot 2025-02-02 at 12 06 29 PM" src="https://github.com/user-attachments/assets/db031007-0eac-4f8a-b09c-7a586cde42b1" />
<img width="754" alt="Screenshot 2025-02-02 at 12 06 42 PM" src="https://github.com/user-attachments/assets/bd886a19-f7ec-4aeb-98fa-880b1d80b785" />

Stacked Bar Chart The generations play a significant role in the suicide cases, and each generation has contributed to the suicide cases over the years. The G. I Generation and Generation Z have been the prominent generations with a high number of suicides reported. The Boomers generation has made a significant count in the suicide cases, but a year of 2010 has been observed with no suicide cases reported for this generation.

Heatmap Suicide rates vary across different generations, as seen in the heatmap. G.I Generation has a higher intensity compared to other generations, but every generation has contributed to the overall suicide cases. Notably, G.I Generation and Generation Z have gaps in their suicide cases during certain periods.

<img width="849" alt="Screenshot 2025-02-02 at 12 07 16 PM" src="https://github.com/user-attachments/assets/5da151ff-9486-4625-a9a5-3d239488ccb9" />
<img width="390" alt="Screenshot 2025-02-02 at 12 07 34 PM" src="https://github.com/user-attachments/assets/548d0ed9-0cd2-4641-86e0-b6fd8c43a7d8" />

The graph presents the highest number of suicides by country. Japan, the Russian Federation, and the United States have the most reported cases.

<img width="928" alt="Screenshot 2025-02-02 at 12 08 00 PM" src="https://github.com/user-attachments/assets/c9604ec1-ada8-42d7-8975-f570ae1fc291" />
<img width="928" alt="Screenshot 2025-02-02 at 12 08 12 PM" src="https://github.com/user-attachments/assets/f89390d6-1481-47a9-809b-66407d31324c" />

The top 10 countries with the highest average suicide rates were analyzed using a donut chart, with Lithuana having the highest rate at 12.8%. Sri Lanka followed closely at 11.2% and the Russian Federation at 11%. These results showcase the severity of the issue in these countries and the need for a closer examination of the underlying factors contributing to the high suicide rates.

On the other hand, the bottom 10 countries with the lowest average suicide rates were also analyzed using a donut chart. Interestingly, there were no recorded suicide rates in countries such as Dominica and Saint Kitts. Jamaica, on the other hand, had the lowest average suicide rate among these countries. These insights highlight the need for continued monitoring of suicide trends and the factors contributing to them, even in countries with low suicide rates, to ensure the well-being of the population.

<img width="714" alt="Screenshot 2025-02-02 at 12 08 35 PM" src="https://github.com/user-attachments/assets/c16d8f95-0229-4d6c-9101-78fe40cb49b1" />

The box plot of suicide rates for the top 10 countries reveals that the distribution of suicide rates is quite varied. Republic of Korea has a high number of outliers, indicating that there is a significant amount of variability in the suicide rates for this country. On the other hand, the Russian Federation has the highest median suicide rate, with a median of 19.13. This highlights that the suicide rate in this country is significantly higher compared to other countries. On the other hand, the suicide rate is the lowest in Brazil, with a median of 2.80. This suggests that the suicide rate in Brazil is relatively low compared to other countries.

<img width="897" alt="Screenshot 2025-02-02 at 12 09 00 PM" src="https://github.com/user-attachments/assets/84fe8c17-16b9-49dc-ac7c-d6b3eaa8fd32" />

The suicide rates vary greatly across countries. In some countries, suicide is a leading cause of death, while in others it is much less prevalent. The countries with the highest number of suicides include Belarus, Hungary, Kazakhstan, Lithuania, Russia, and Sri Lanka, with a higher number of male suicides compared to female. The age group with the highest number of suicides is 35 to 54 years. In Kazakhstan, the highest suicide rate is in the 5 to 14 years age group, while in Sri Lanka, females in the same age group have a higher rate of suicides than males.

<img width="845" alt="Screenshot 2025-02-02 at 12 09 21 PM" src="https://github.com/user-attachments/assets/60bd6ca3-c2b6-4669-995d-1286b31a8a0d" />

On the other hand, countries with the lowest suicide rates include Antigua and Barbuda, Cabo Verde, Dominica, Grenada, Macau, Maldives, Oman, Saint Kitts and Nevis, and San Marino. Saint Kitts and Dominica have zero reported suicides, while Oman and San Marino have no reported suicides among females. Maldives also has zero suicides reported in the 55 to 74 years age group. The population size and demographic factors play a significant role in determining the suicide rate of a country.

### Section 2: Economic Analysis based on Suicide Cases

<img width="800" alt="Screenshot 2025-02-02 at 12 09 54 PM" src="https://github.com/user-attachments/assets/5d8ba4ff-2661-416a-87b1-fddb9325c370" />

The analysis shows a significant difference in the distribution of GDP per capita among the top 10 countries. Luxembourg stands out as the country with the highest GDP per capita, while the United States has the lowest GDP per capita among the top 10 countries. This indicates that there is a wide range of economic development among these countries, and that the level of economic prosperity can greatly impact the standard of living and overall well-being of the population.

<img width="890" alt="Screenshot 2025-02-02 at 12 10 14 PM" src="https://github.com/user-attachments/assets/88e961c3-487b-4786-bda9-fb9cefcd5f91" />

There appears to be a correlation between the GDP per capita of a country and its suicide rate. Countries with higher GDP per capita tend to have lower suicide rates, such as Slovenia. On the other hand, countries with lower GDP per capita, such as Sri Lanka, tend to have moderate to high suicide rates. An interesting exception is seen in Ukraine, which has the lowest suicide rate but also the lowest GDP per capita.

<img width="890" alt="Screenshot 2025-02-02 at 12 10 40 PM" src="https://github.com/user-attachments/assets/6e9f01a0-d023-4ac9-8341-de20fc3d93a9" />

The correlation between a country’s GDP per capita and its suicide rate is apparent. Dominica has both low GDP per capita and low suicide rate, while United Arab Emirates has high GDP per capita but also high suicide rate. Oman presents a moderate balance between the two variables.

Based on the above insights, it can be concluded that there is not a clear relationship between the GDP per capita and the suicide rates of countries. Some countries have high GDP per capita and low suicide rates, such as Slovenia and the United Kingdom. Other countries have low GDP per capita and high suicide rates. There are also countries that fall in between with moderate rates of both variables, such as Oman. This indicates that there may be other factors that play a role in determining suicide rates, and that a high GDP per capita does not necessarily equate to low suicide rates and vice versa.

<img width="900" alt="Screenshot 2025-02-02 at 12 11 03 PM" src="https://github.com/user-attachments/assets/3627fae7-9fb8-492c-a113-85eac0342311" />

It can be concluded from the above observations that there is no clear pattern that can be drawn between the GDP per capita and the number of suicides in a country. In some countries, like Brazil, Poland, and South Korea, there is an increase in the number of suicides with an increase in GDP per capita, while in other countries, such as France, Germany, Russia, Ukraine, and the United States, the number of suicides decreases with an increase in GDP per capita.

<img width="900" alt="Screenshot 2025-02-02 at 12 11 23 PM" src="https://github.com/user-attachments/assets/a4890ffc-efd1-4089-ac8b-f20889ff6601" />

Due to the scattered data points and limited information on suicides and GDP per capita for the countries, it is difficult to draw any meaningful conclusions from this information.

The relationship between GDP per capita and the total number of suicides is complex and can vary greatly between countries. In some cases, an increase in GDP per capita can lead to a decrease in suicides, while in other countries an increase in GDP per capita can lead to an increase in suicides. The relationship between these two variables is not clear and likely depends on various social, cultural, and economic factors. Thus, it is important to consider multiple factors and not rely solely on GDP per capita when examining the issue of suicide.

<img width="854" alt="Screenshot 2025-02-02 at 12 11 47 PM" src="https://github.com/user-attachments/assets/327a29bc-dbba-4454-b567-3697678a06c2" />
<img width="854" alt="Screenshot 2025-02-02 at 12 12 01 PM" src="https://github.com/user-attachments/assets/df6aefe4-a42e-4488-82da-0fb77ad81ebf" />

GDP_per_Capita VS Year : Through this plot, it is apparent that the evolution of GDP per capita differs greatly among countries. In the case of Ukraine, the GDP per capita remains largely unchanged and remains at a low level. On the other hand, the United States experiences a significant increase in GDP per capita over time, with a noticeable leap at certain points. Meanwhile, Japan’s GDP per capita exhibits a fluctuating pattern, with alternating periods of increase and decrease.

Suicides VS Year : This plot provides a visual representation of the trend of suicides in different countries over time. In the case of Japan, there is a noticeable decrease in suicides from 1986 to 1997, followed by an increase from 1998 onwards. Meanwhile, in the United States, the trend seems to indicate a steady increase in suicides starting from 2004. Overall, the plot highlights the fluctuations in the number of suicides in different countries and allows for a better understanding of the trends and patterns in each country.

### Correlation Analysis (Integrating the above Sections)

<img width="670" alt="Screenshot 2025-02-02 at 12 12 39 PM" src="https://github.com/user-attachments/assets/58eca586-9080-4e60-8450-8d615486b4e3" />

The correlation heatmap provides an insightful representation of the relationship between different numerical variables in the dataset such as year, number of suicides, population, suicide rate, GDP per Year, and GDP per Capita. Through this visualization, it became evident that there is a strong positive correlation between population and number of suicides, which is reflected in the high correlation with GDP per Year. Additionally, the heatmap highlights a clear negative correlation between the number of suicides and the year, indicating a decline in suicide cases over time.

## 🚀 How to Run This Project

### 1️⃣ Clone the Repository

git clone https://github.com/YOUR_GITHUB_USERNAME/Hackathon-Suicide-Analysis.git

### 2️⃣ Install Required R Packages

install.packages(c("tidyverse", "ggplot2", "dplyr", "readr", "corrplot", "ggthemes"))

### 3️⃣ Run the Analysis in RStudio

1. Open Hackathon_in_R.Rmd in RStudio
2. Run the code chunks or Knit the document

## 📢 Conclusion & Recommendations

✅ Strengthening mental health support in high-risk demographics.

✅ Job security policies to mitigate economic stress impacts.

✅ Suicide prevention programs tailored to age and gender groups.

✅ Leveraging data science to improve early detection & intervention strategies.

## 🎯 Future Scope

🔹 Applying Machine Learning models to predict suicide risks.

🔹 Enhancing data granularity with regional-level insights.

🔹 Integrating social media sentiment analysis for real-time risk assessment.

## 👏 Acknowledgments

A huge shoutout to Northeastern University and Professor Mohammed Dehgani for hosting this insightful event! 🙌
