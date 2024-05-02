# Unveiling-Flight-Disruption-Insights

![Image](https://github.com/tanvi-sheth/Unveiling-Flight-Disruption-Insights/assets/144172508/c5278a1e-408f-467d-8f53-b72969434ef9)

## Executive Summary
Analyzing flight data offers invaluable insights into the operational dynamics of the aviation industry, providing stakeholders with crucial information to optimize resources, enhance efficiency, and improve customer experience. By exploring delay and cancellation patterns by airline, airport locations and over time and seasonality, we can gain a macro-level understanding of the challenges and opportunities within the aviation ecosystem.

The primary objective of this project is to explore and analyze the various aspects that contribute to flight delays or cancellations. We aim to identify trends for various airlines and airports and provide insights into the root causes of flight delays and cancellations.

The analysis in this report focuses more on the macro factors and a bird-eye analysis of the various domains where we pay more attention to three factors related to flight delays and cancellations: airlines, airports and timing and seasonality. In this project, we dive deeper into the patterns for each of these factors and understand if there are any particular areas for improvement. 

Based on our current exploration, we see that the major delays and cancellations are prevelant in regional airlines, while the well-known internationally operating airlines seem to working with efficiency. However, this is a preliminary observation and more analysis will provide better insights into the actual patterns and functions of the airlines. For the time of day analysis, we see that most of the delays occur later in the evenings and we would like to further figure out if these delays and cancellations are caused due to controllable factors like scheduling and planning or uncontrollable factors such as weather conditions like storms. We also take a look at the most frequent routes to understand flyer behavior. This will help improve the operations of airlines for these routes and even provide the airports with some insights so that they can be better prepared to avoid delays and cancellations.

## Motivation
We've all experienced the frustration of flight delays, which can lead to significant inconvenience. Through this project, our goal is to identify the factors contributing to delays or cancellations and detect any patterns unique to specific airlines or airports. By doing so, we aim to enhance airline operational efficiency, improve passenger experience, and mitigate the economic losses associated with flight disruptions.

## Problem Definition
Our project aims to utilize a rich dataset containing flight delay and cancellation information to address several critical objectives. Firstly, we will conduct a thorough analysis of delays over time, examining specific patterns related to airlines or airports. By analyzing historical data, we intend to uncover recurring trends and seasonal variations, providing valuable insights into the factors influencing flight schedules and punctuality.

Secondly, we will delve into the root causes of flight delays, identifying primary factors contributing to disruptions and assessing how these trends evolve over time. Through detailed examination and advanced analytics techniques, we seek to gain insights into the top reasons for delays, including inclement weather, air traffic congestion, mechanical issues, and crew scheduling constraints.

Lastly, we aim to develop predictive models capable of forecasting future flight cancellations or delays, along with estimating the approximate duration of these disruptions. Leveraging predictive analytics and machine learning algorithms, our goal is to provide stakeholders with actionable insights for proactive planning and risk mitigation strategies. Additionally, we intend to offer passengers optimal travel time recommendations based on our analysis, enabling them to make informed decisions and minimize the impact of disruptions on their travel plans.

In summary, our project endeavors to harness data-driven insights to enhance operational efficiency, improve passenger experience, and mitigate economic losses associated with flight disruptions. By analyzing flight delay and cancellation data comprehensively, we aim to provide valuable insights and recommendations that benefit both airlines and passengers, ultimately contributing to smoother and more reliable air travel experiences.

## Dataset & Data Source
The dataset is from Kaggle, retrieved from https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022?select=Airlines.csv. The dataset was extracted from the Marketing Carrier On-Time Performance data table of the "On-Time" database from the TranStats data library (https://www.transtats.bts.gov/). Our dataset contains 6 files ranging from 2018 to 2022, with a size of about 10 GB in total.

Data Overviews
In the dataset we made use of 6 tables: 2018 Flights with 5,689,512 rows, 2019 Flights with 8,091,684 rows, 2020 Flights with 5,022,397 rows, 2021 Flights with 6,311,871 rows, 2022 Flights with 4,078,318 rows and an `Airports` table with descriptions about each airport. Each of the table gives us the detailed information about the flight status with respect to the cancellations and delays. Before diving deep into the data understanding the columns descriptions with respect to the tables is an important part of the process. The following tables give us a view of the datasets. 

