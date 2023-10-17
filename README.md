# FAO-AQUASTAT-Dissemination-Project

## Introduction 

For this project I wanted to visualize some geographic and population data and I found the FAO AQUASTAT Dissemination database: [link](https://data.apps.fao.org/aquastat/?lang=en). This site provides free access to over 180 variables and indicators by country from 1960 to 2020. These variables are related to geography and population, pressure on water resources, environment and health, irrigation and draingage development, water resources, and water use. I chose to work with a selection of interesting variables from the geography and population section. I decided to create three dashboards: social metrics, economic metrics, and agricultural metrics. All three of these visualize data from 2020 as well as the trend of a few of the variables over multiple year stretches. 

## Interact With The Dashboard!
To view the full dashboard and to interact with it, check it out at my Tableau Public Profile: [link](https://public.tableau.com/app/profile/owen.patrick/vizzes).

## Dashboard Screen Shots & Analysis

![Social Metrics](https://github.com/Owenp25/FAO-AQUASTAT-Dissemination-Project/assets/77632947/e72b5136-6be7-4466-a786-005ede564035)

I find it interesting that Niger and Chad are both in the bottom 5 for gender inequality index (GII) and human development index (HDI): this makes me want to research these countries further and find out what the root causes of such poor gender equality and platforms for development are. It is also important to note that the indices for these 5 countries have not fluctuated much in the past 10 years. On the flip side, Norway, Switzerland, and Germany are very highly ranked in both GII and HDI. I would be interested to look further into the numbers and see what other metrics these countres are succeeding in.

![Economic Metrics](https://github.com/Owenp25/FAO-AQUASTAT-Dissemination-Project/assets/77632947/ce10237b-051d-4fc9-a280-886ede70e109)

The difference in GDP per capita between the top 5 and bottom 5 countries is truly astonishing. To see them right next to each other shows just how much countries like Somalia, Burundi, and Mozambique need financial, governmental, and infrastructural support. Looking at inflation, there is a very diverse array of countries. The formula for GDP Price Deflator is this: (Nominal GDP ÷ Real GDP) × 100. The nominal GDP is found with the current year prices while the real GDP is found with the base year prices, which is 2015 in this case. This is is why I only looked at the countries with high inflation dating back to 2016. Inflation is all about context-- high inflation could mean economic instability or it could mean a period of rapid economic growth. Because of this, I think my dashboard is a good jumping off point to go research more about these high and low inflation countries and understand the context.

![Agricultural Metrics](https://github.com/Owenp25/FAO-AQUASTAT-Dissemination-Project/assets/77632947/28a9ab49-fdfc-45cd-976d-c65cdc679128)

There is startling difference between the number of undernourished people in the top 5 countries versus the worldwide average in 2020. India had about 31.5 times more undernourished people than the worldwide average in 2020. Looking at the 10 year trend for these top 5 countries, there is a spike in undernourished people in 2012 in China, although this number has dropped slightly throughout the years since then. One intriguing thing I noticed about the percent of land cultivated is that there are small island nations in both the top and bottom 5. Tuvalu is very cultivated while the Faroe Islands is not at all. Of course, this is due to climate and geographic location. I thought looking at the trend of the most cultivated nations may show some countries that are rapidly developing in terms of agriculture but it appears that the percent of area cultivated did not change much between 2010 and 2020 for these countries.

## SQL Portion of Project
In addition to using Tableau, I used Microsoft SQL Server to query the same exact information included in my dashboards. I did this to make sure that I had the correct number in my visualizations-- ensuring accuracy is always important, especially when calculations are involved. The full PDF of this SQL code is attached as a PDF in the repository.

Preview of SQL statements:
![SQL pic](https://github.com/Owenp25/FAO-AQUASTAT-Dissemination-Project/assets/77632947/0f9f2ec3-9e4e-43c7-a2bb-d4854d15a015)
