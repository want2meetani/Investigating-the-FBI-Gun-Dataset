
# Investigate-FBI-Gun-Data

This project explored trends of U.S gun purchases and its relationship with census variables and transformed, combined and visualized gun and census datasets using NumPy, Pandas and Matplotlib


Introduction

Data Wrangling

Exploratory Data Analysis

Conclusions

FBI Gun and census data are two independent table. Their common variables/value include state of United States and year month, which requires data cleaning at first. I joined these two dataset to see the relationship between gun purchase and census variable.

***Description***

The data in this repository comes from the FBI's National Instant Criminal Background Check System. The NICS is used to determine whether a prospective buyer is eligible to buy firearms or explosives. Gun shops call into this system to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase. The data has been supplemented with state level data from census.gov.

Mandated by the Brady Handgun Violence Prevention Act of 1993 and launched by the FBI on November 30, 1998, NICS is used by Federal Firearms Licensees (FFLs) to instantly determine whether a prospective buyer is eligible to buy firearms or explosives. Before ringing up the sale, cashiers call in a check to the FBI or to other designated agencies to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase. More than 100 million such checks have been made in the last decade, leading to more than 700,000 denials.

***Findings for the Quesitons:***

1.The gun and census data are divided by state with United state. High gun per capita should also be calculated by state, except {'District of Columbia','Guam','Mariana Islands','Puerto Rico','Virgin Islands'}. these states' gun total is missing or zero. Among all the state, Kentucky has the highest gun per capita on Jul 2016 and Apr 2010 data. Kentucky,Indiana,Illinois,West Virginia,Montana are the top 5 state who have highes gun per capita on Jul 2016. also, based on the scatter plot for all the fact value in one figure and group by column name scatterplot,there is no strong association between any fact value and high gun per capita. However, based on the scatter plot for fact varible and gun per capita, separately, there is some weak association found as following; the positive association between gun per capita and variables which includes: White alone, percent, July 1, 2016, (V2016) Persons 65 years and over, percent, April 1, 2010 owner-occupied housing unit rate, 2011 -2015 the negative association between gun per capita and variables which includes: 2011-2015 Asian alone, percent, July 1, 2016, (V2016) Foreign born persons, percent, 2011-2015 Median gross rent, 2011-2015

2.Alaska had the highest growth in gun registrations in Jul 2017, increasing by 403.20% compare to Apr 2010. Additionally,Alaska,Wyoming,Montana,Kansas,Arkansas are the top 5 state with highest growth in gun registrations in Jul 2017.Alaskas and Wyoming are only two state whose growth more than 400%. also from the gun growth bar chart for all the states, we can see Utah and Indiana are the only two states whose gun growth are descreasing by more than 100%. On the other hand, there are 8 states' gun growth more than 300%, which can be considered outliers.

3.From the line chart for gun purchases by years, we can tell that from 1998 to 2016, the overall of gun purchases is increasing. From 1999 to 2005, the number of gun purchases remains stable, and from 2005 to 2016, the number of gun purchases increase from about 10 million to 2.7 million. From 2016 to 2017, the number of gun purchases goes down, which is partially due to only 9 months in 2017 being calculated.
