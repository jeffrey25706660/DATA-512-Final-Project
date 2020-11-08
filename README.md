# Data 512 Final Project Proposal

Asian American is the fastest-growing racial group in the United States according to the research by Pew Research Center. The City of Austin in Texas is no exception. The majority of the group is still immigrants. Once here, Asian immigrant families face many obstacles, such as language barriers, culture shock, and ongoing adjustments to new lives. One of the most prevalent issues that most immigrants face is racism and discrimination. Many studies have found that racism has been linked with increased risk of health and lower satisfaction of life. The survey conducted by the City of Austin collects data from 230 different questions from the Asian immigration group to help us better understand their social and life experience in the United States and the basis of a personal characteristic that causes the immigration group to be treated unfairly.

# Selected Data for analysis
The data contains more than 2000 rows and 230 attributes collecting from the surveys the city government sent out in 2020. The questions accurately measure the respondents' opinions, behaviors, and experiences. The demographic data regarding age, gender, marital status, etc is also retrieved. Few ethical considerations that may arise in the project include potential gender and age bias in the data.

The dataset can be collected through API here: https://data.austintexas.gov/City-Government/Final-Report-of-the-Asian-American-Quality-of-Life/hc5t-p62z

Terms of Service: https://austintexas.gov/page/city-austin-open-data-terms-use

# Unknowns and dependencies
Two factors can impede the project progress, the variable selections and data connectivity. The data contains more than 200 attributes, it will require time-consuming EDA analysis to select the best subset of the variables. The data is retrieved through an API interface without guaranteeing the data availability. The owner may shut off the access without giving any notice.

# Research questions
1. How does the experience racial discrimination across age and have an effect on the quality of life among the Asian American community?
2. Does limited English proficiency lead to racial discrimination across gender?
3. Does the wage difference correlate with experience of racial discrimination among Asian Americans?

# Related Work
One of the most prevalent issues that most immigrants face today is racism and discrimination. According to the study by Yoo, Gee, and Takeuchi investigating discrimination within an Asian American community, 21% of the respondents reported being racial discriminated because of their race, language, and accent. The other study researched by the same group of researchers indicates that racial discrimination has been recognized as a key determinant of mental disorders and depressive symptoms. The project will examine different numbers of personal characteristics, including income level, marital status, and age to identify the factors behind the discrimination in the Asian immigration group in the City of Austin, Texas. The outcome of the analysis will help the city improve race relations and ensure equal treatment.

# Methodology
The methodology for this project focuses on the mix of descriptive and regression analysis to understand the basis of a personal characteristic that causes racial discrimination among Asian immigrant families.

The survey data is a two-dimensional data structure with organized rows and columns which is well-suited for both methods. Each entry of which represents a respondent's answer to the survey questions, making it efficient to manipulate and perform a regression analysis at different levels. For example, the descriptive approach will compute the percentage of racial discrimination experienced as well as the average quality of life across age and gender. The linear regression model will provide important evaluation metrics that allow us to describe the relationship between one or more predictor variables and the response.

# References:
[1]Gee GC, Spencer M, Chen J, Yip T, Takeuchi DT. The association between self-reported discrimination and 12-month DSM-IV mental disorders among Asian Americans nationwide. Social Science & Medicine. 2007b;64:1984–1996. Retrieved from https://www.researchgate.net/publication/227914163_Strangers_Still_The_Experience_of_Discrimination_Among_Chinese_Americans

[2]Yoo HC, Lee RM. Ethnic identity and approach-type coping as moderators of the racial discrimination/well-being relation in Asian Americans. Journal of Counseling Psychology. 2005;52:497–506. Retrieved from https://psycnet.apa.org/record/2005-13343-006
