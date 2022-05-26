# Data Analytics Portfolio
Data Analytics Portfolio - Exploratory Data Analysis (Excel, Python) and Dashboards (Tableau and Google Data Studios)

# [Project 1: Excel - Linear Regression of Relative Size of Service Sector vs GDP per Capita](https://github.com/AlexHumpert/GDP-Capita_vs_Service_Sector)
“Structural Transformation” is a theory in economic development that makes the following prediction: "as a country's economic activity shifts from agriculture, to manufacturing to the services sector, gdp per capita will rise". Is this relationship statistically sound? Can we provide policy makers with data-driven insights to help decision making?

We test this by running a linear regression with service sector value added (% of GDP) as the explanatory variable and wealth (using GDP/K as a proxy indicator) as the target variable on a cross-sectional sample of 184 developing and developed countries. We find a moderately strong, positive linear relationship **(r = 0.58)** between the variables, however the **linear regression model only explains 29% of the variation** in the target, despite residuals being white noise.

Although we may infer a positive relationship bewteen the two variables, our model does a poor job of explaining the target (which is to be expected given the domain covered and narrow features used). However, adding more relevant explanatory features, such as proportion of labor force with advanced education and the proportion of population with internet access, may help produce a better model.



# [Project 2: Tableau - Dashboard of GDP & C02 Emissions per Capita](https://public.tableau.com/profile/alex.h#!/vizhome/CapitaxCO2Dashboard/Dashboard)
Gapminder maintains a database of historical economic development data for countries around the world. The following Tableau dashboard displays relationships between  economic, demographic and CO2 emissions data for countries across the world. Some insights from a first glance of the dashboard are the following: 
* GDP per capita is positively linked to CO2 emissions per capita.
* To significantly curb C02 emissions, wealthier industrialized countries will need to lead the way.

# [Project 3: Tableau - EDA of State of Iowa Liquor Sales](https://public.tableau.com/profile/alex.h#!/vizhome/iowa_liquor/Story2)
For the final project of a one-week Data Analytics Bootcamp at General Assembly, NYC, students were asked to explore the state of Iowa's SQL liquor sales database. The following are some of the insights derived from the exploration:
* State-wide sales trends are driven by Polk county trends given its large population size. 
* Dickinson county has the largest sales per capita and at the same time is the county with the second smallest yearly sales.
* Dickinson county sees just over 90% of its sales on Tuesday and a 20,000% spike in sales from Friday to Saturday. 

# [Project 4: Python - EDA of Jain University Job Placements](https://github.com/AlexHumpert/EDA_Jain_University_Placements)
Explored a dataset of dataset of MBA graduates from the Jain University in Bangalore. The owner of the dataset, Ben Roshdan, a graduate of the university himself, uploaded the dataset on Kaggle asking for the community to help him find insights. Some of the insights made are:
* The graduate employment rate is 68%. 
* The factors that influence employment outcomes the most are: 
 * Previous work experience
 * The Marketing with Finance MBA specialization is better than the Marketing with HR specialization. 
 * The Commerce or Science Undergraduate degree is better than any of the "Other" degrees. 

# [Project 5: Python - EDA of Fatal Police Shootings](https://github.com/AlexHumpert/EDA_Fatal_Police_Shootings)
Explored a dataset of fatal police shootigs collected by the Washington Post since January 1, 2015. Some of the insights made are:
* The typical victim of a fatal police shooting is a 34 year-old white, male with indications of mental illness. He is most likely to be shot in January while armed and attacking officers.
* Although representing just 13% of the total US population, African Americans are significantly overrepresented in fatal police shooting data, representing 26% of all fatal police shootings.
* Just the top four states California, Texas, Florida and Arizona, account for approximately 33% of all police shootings in the USA. 





