# Discrimination In the United States: Experiences of Asian Ethnic Group in the City of Austin

## Abstract
Asian American is the fastest-growing racial group in the United States according to the research by Pew Research Center. The City of Austin in Texas is no exception. According to the data released by the government of Austin, the number of Asians in Austin is doubling every 10 years compared with the general population which doubles every 20 to 25 years. Yet, the majority of the group is still immigrants. Once here, Asian immigrant families face many obstacles, such as language barriers, culture shock, and ongoing adjustments to new lives. One of the most prevalent issues that most immigrants face is racism and discrimination. Many studies have found that racism has been associated with increased risk of health and lower satisfaction of life. The survey conducted by the City of Austin collects data from 230 different questions from the Asian immigration group to help us better understand their life experience and the basis of a personal characteristic that causes the immigration group treated unfairly in the United States. The methodology for this project focuses on the mix of descriptive and regression analysis to identify outliers, summarize the characteristics in a meaningful way, and discover the relationship between one or more predictor variables and the response. The key findings from our research show that the respondent's prior experience in racial discrimination does not have a statistically significant relationship with quality of life in the City of Texas. On the contrary, our study also indicates that regardless of English speaking ability and income level, a high percentage of individuals from the Asian immigration group still report being discriminated against in any way.




## Data Sources
The data contains more than 2000 rows and 230 attributes collecting from the surveys the city government sent out in 2020. The questions accurately measure the respondents' opinions, behaviors, and experiences. The demographic data regarding age, gender, marital status, etc is also retrieved. 

The dataset can be collected through API here: https://data.austintexas.gov/City-Government/Final-Report-of-the-Asian-American-Quality-of-Life/hc5t-p62z

Terms of Service: https://austintexas.gov/page/city-austin-open-data-terms-use


# Research questions
1. How does the racial discrimination have an effect on the quality of life across age among the Asian immigration group?

![alt text](https://github.com/jeffrey25706660/Data-512-final-project/blob/main/regression%20analysis.png)
![alt text](https://github.com/jeffrey25706660/Data-512-final-project/blob/main/age_group_vs_discrimination.png)

2. Does limited English proficiency lead to racial discrimination?

![alt text](https://github.com/jeffrey25706660/Data-512-final-project/blob/main/English_Speaking_vs_Discrimination.png)

3. Does the wage difference correlate with experience of racial discrimination among Asian ethnic group?
![alt text](https://github.com/jeffrey25706660/Data-512-final-project/blob/main/Income_Level_vs_Discrimination.png)

# Related Work
One of the most prevalent issues that most immigrants face today is racism and discrimination. According to the study by Yoo, Gee, and Takeuchi investigating discrimination within an Asian American community, 21% of the respondents reported being racial discriminated because of their race, language, and accent. The other study researched by the same group of researchers indicates that racial discrimination has been recognized as a key determinant of mental disorders and depressive symptoms. The project will examine numbers of personal characteristics, including income level, marital status, and age to identify different factors behind the discrimination in the Asian immigration group in the City of Austin, Texas. The outcome of the analysis will help the city improve race relations and ensure equal treatment to its people.

# Methodology
The methodology for this project focuses on the mix of descriptive and regression analysis to understand the basis of a personal characteristic that causes racial discrimination among Asian immigrant families.

The survey data is a two-dimensional data structure with organized rows and columns which is well-suited for both methods. Each entry of which represents a respondent's answer to the survey questions, making it efficient to manipulate and perform analysis at different levels. We will begin with a descriptive analysis to identify outliers and detect typos in the survey data. Then, we will use the same method to summarize the characteristics of the data in a meaningful way. For example, we will calculate the average number of discrimination per person across different age groups as well as including the average quality of life in the analysis. We will also refine our calculation to compute the percentage of racial discrimination experienced across gender and marital status. Lastly, we will introduce the linear regression model to the project. Linear regression is an extremely powerful way of discovering the relationship between one or more predictor variables and the response. The method provides important evaluation metrics such as regression coefficients and p-values. We will be interpreting the outputs carefully to understand what factors are significant predictors of the outcome variable; i.e., the quality of life and the average number of racial discrimination among the Asian immigration group.

# References:¶
[1]Gee GC, Spencer M, Chen J, Yip T, Takeuchi DT. The association between self-reported discrimination and 12-month DSM-IV mental disorders among Asian Americans nationwide. Social Science & Medicine. 2007b;64:1984–1996. Retrieved from https://www.researchgate.net/publication/227914163_Strangers_Still_The_Experience_of_Discrimination_Among_Chinese_Americans

[2]Yoo HC, Lee RM. Ethnic identity and approach-type coping as moderators of the racial discrimination/well-being relation in Asian Americans. Journal of Counseling Psychology. 2005;52:497–506. Retrieved from https://psycnet.apa.org/record/2005-13343-006

[3] The City of Austin. Top Ten Demographic Trends in Austin, Texas. Retrieved from https://www.austintexas.gov/page/top-ten-demographic-trends-austin-texas; https://www.austintexas.gov/sites/default/files/files/Planning/asians_by_origin.pdf

[4] Pew Research Centery. Key facts about Asian Americans, a diverse and growing population. Retrieved from https://www.pewresearch.org/fact-tank/2020/05/07/asian-americans-are-the-fastest-growing-racial-or-ethnic-group-in-the-u-s-electorate/
