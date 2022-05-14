# GunMortalityAnalyticsProject

## Data Source
This project uses data from fivethirtyeight’s “guns-data” repository. The repository contains already cleaned and parsed data from the CDC's Multiple Cause of Death data file. The dataset includes information on 100,000+ victims of gun-related fatalities  from the years 2012-2014 in the United States. The gun-related deaths of Non-U.S residents are excluded from the data set as per CDC's practice. The police column, which states whether a victim was a police officer or not, is derived from Federal Bureau of Investigation's(FBI) Uniform Crime Reporting publications (UCR). The UCR includes the killings of federal, state, and local law enforcement officers who were sworn officers, normally carried a gun and badge, and had full arrest powers.


## About
Using the information from the data set, I wanted to answer 6 questions: 
- What is the relationship between the victim's race and the intent behind their death?
- How many deaths are there for each race?
- What is the most common intent behind the gun-related deaths of the women in the dataset? 
- What is the average age of both men and women in the data set?
- Can one accurately predict a victim’s race given the age of the victim and the intent behind their death?
- Does the time of year have any relation to the intent behind a victim’s death? 

When answering these questions, I used the following libraries: tidyverse, ggplot2, modelr, and e1071 (includes the svm function). These libraries were used to assist me in the process of visualizing the data, creating predictive models of the data, and the overall process of exploring the data. 
