# TicketMaster Concert Pricing Analysis 2021
This repository houses the analytic study and data models for the "TicketMaster Analysis of 2021 Concerts," a project that delves into the factors influencing concert ticket pricing on the TicketMaster platform. The analysis aims to uncover the variables that significantly impact the minimum price of concert tickets, offering insights for consumers and industry stakeholders.

## Project Overview
The analysis concentrates on TicketMaster, a leader in the global ticket marketplace, particularly focusing on the minimum price of concert tickets. By examining various attributes such as artist popularity, city population, venue, genre, and event timing, we aim to answer pivotal research questions regarding the determinants of ticket pricing.

## Objectives
1. Assess the influence of venue size and city population on ticket prices.
2. Examine the effect of artist popularity and genre on the pricing structure.
3. Investigate the pricing trends over time and during specific seasons.
4. Utilize hypothesis testing and linear regression analysis to validate findings.

## Methodology
1. Data Acquisition: Utilized the TicketMaster API to collect a robust dataset encompassing city, artist, venue, event timing, and ticket prices.
2. Data Preprocessing and Cleaning: Implemented data cleaning techniques to ensure data quality for the analysis.
3. Statistical Analysis: Conducted hypothesis tests (T-Test, Chi-Square, ANOVA) to draw inferences about the population data from samples.
4. Predictive Modeling: Applied multiple linear regression models to predict ticket pricing based on the identified influential factors.

## Key Findings
1. Artist and venue popularity have a substantial impact on the pricing of tickets.
2. Ticket prices tend to peak during specific seasons, with notable variances across different cities.
3. Event timing (weekend or weekday) also plays a role in the ticket pricing strategy.
4. Through linear regression analysis, we identified that the artist's popularity score and city population were significant predictors of ticket prices.

## Repository Contents
1. Analytic Report: A comprehensive document detailing the analysis process, findings, and recommendations.
2. Data Set: The collected data from TicketMaster, including features such as artist ratings, venue sizes, and ticket prices.
3. R Scripts: The code for data cleaning, visualization, hypothesis testing, and linear regression models.
4. Visualizations: Graphs and charts that illustrate the relationships between different variables and ticket pricing.

## Limitations and Future Scope
1. The analysis is bound by the data available through the TicketMaster API and the timeframe of 2021.
2. Further research could expand to include additional variables, such as marketing spend, artist engagement activities, and secondary market influences.
3. Advanced predictive models and machine learning algorithms could be employed to enhance predictive accuracy.