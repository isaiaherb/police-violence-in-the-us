# Police Violence in the US (2013-2019)
## Executive Summary
## Objective
## Dataset
Dataset from Kaggle: 
- https://www.kaggle.com/datasets/jpmiller/police-violence-in-the-us
- https://www.kaggle.com/datasets/jpmiller/police-violence-racial-equity
### Description
This is a series that pulls together data from several different sources regarding police-related violence and racial equity in the United States. The datasets currently include these types of data:

Part 1: Citizen deaths, police deaths, and other outcomes
- Police shootings
- Citizen fatalities involving police
- Police officer deaths suffered in the line of duty
Part 2: Demographics, crime stats, protests, and other data
- Social and economic data
- Political leanings of citizens
- Sales of DoD equipment to law enforcement agencies
- City budgets
- Police department headcounts
- Police department policies and contract provisions
- Juvenile arrests by type of crime and race
- Crimes and arrests for the prime city in the four largest metro areas.
- Protest activity
- Police response
- Press activity
- Video clips of incidents

## Methodology
This project studies a few of the root causes behind high police homicide rates and high crime rates, including racial and political demographics, police and city budgets, poverty, education, and so on. By extracting and analyzing data related to these topics, we hope to uncover some of the underlying sources of police violence. We recognize police violence is a highly sensitive topic, and this analysis only begins to scratch the surface of how police violence can be further understood and prevented. The data extraction, cleaning, and storing processes are relatively straightforward. Using a source dataset from Kaggle, the selected files were then cleaned in Python using primarily using pandas, transformed into tables, and loaded into a Postgres database. This database was then further queried using SQL to find meaningful insights. 

## Questions
- police killing by race as a percent of total population with the corresponding race
- racial dissimilarity index
- violent crime and total arrests
- total killed by police
- total below poverty level
- how does a city's wealth and spending trends correspond to violent crime
- how many shootings in each city where the victim was unnarmed, not fleeing, or in their car, how many are justified, and what is the racial trend
- what is the root cause of police violence, is it funding, political division, high crime or murder rates, high poverty, low education, type of crime, or something else
## Findings
