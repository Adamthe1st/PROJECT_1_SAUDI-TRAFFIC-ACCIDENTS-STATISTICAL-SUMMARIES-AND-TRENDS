# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Local Traffic, Statistical Summaries and Inference

---

### Problem statement

Safe roads are what everyone desires. Safe roads are not for luxury or convenience, they are simply a given for a functional society. Sadly, there have been many recorded fatal road accidents in addition to countless road injuries in Saudi Arabia in recent years. To ensure the safety of ourselves and our loved ones, proper road safety measures should be rigorously reinforced. This report aims to analyze traffic accidents and driving licenses per region in Saudi Arabia and offers policy recommendations based on statistical observations of current affairs.

### Summary facts

- in 2016-2017, the average traffic accident counts in Saudi Arabia was 13868 accidents
- Over the years from 1993-2017, the average driving license count was 28915 driving licenses
- The highest number of traffic accidents was in Makkah in 2017 with accidents count of 145541
- The highest number of driving licenses was in Riyadh in 2017. license count:495307
- The lowest driving license count was 915 in Tabouk in 2015
- The lowest traffict accident count was the Northren border in 2017
- There is a positive correlation between the years 2016 and 2017 with regards to obtained driving licenses
- More accidents were recorded in 2017 compared to 2016


### Recommendations

- Additional steps should be taken to pass driving license tests across the kingdom, especially in highly populated regions such as Makkah and Riyadh.
- Effective use of speed cameras and seat belt checks should be implemented in highly populated areas to reduce speed and control safety on the roads
- Implement traffic rules courses in junior and high schools as mandatory for both genders
- The Ministry of Transport is highly advised to Invest in public transport facilities as this will improve road safety by reducing traffic jams. Finally, the effective use of public transport alighs well with vision 2030 in transforming Saudi Arabia into a digital and eco-friendly way.

**Issues:**

The data used contains some outliers as indicated by box-plots in corresponding jupyter notebook. Thus, future investigations should therefore conduct further analysis to rule out outliers to confirm current conclusions.

---

### Data dictionary

|Feature|Type|Dataset|Description|
|:-|:-|:-|:------------:|
|accident_year|*int*|accidents_df|year in which traffict accidents occurred|
|region|*object*|accidents_df & licenses_df|region of traffic accident or issued driving license|
|accident_outcome|*object*|accidents_df|outcome of accidents - dead/injured|
|accident_count|*int*|accidents_df|number accidents|
|x_point|*float*|accidents_df & licenses_df|x coordinate location of accident or issued driving license|
|y_point|*float*|accidents_df & licenses_df|y coordinate location of accident or issued driving license|
|licese_year|*int*|licenses_df|year of issued driving license|
|license_count|*int*|licenses_df|number of issued driving licenses|

---
#### FOLDERS

 - **code**: contains technical report of statistical analysis and visualizations in jupyter notebook named "Project 1_ Driving Licenses_Traffic_Accidents_and_Casualties_Analysis"
 - **data**: contains all data files used in .csv format
 - **images**: contains images used in the blog post






#### Blog post
Kindly, review this [link](https://ksatrafficadaah.blogspot.com/2021/01/together-towards-safer-roads-in-saudi.html) for an interesting read about key findings of this report


#### Data source

Please click [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/) to visit the original source for traffic accident data

Please click [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/) to visit the original source for the driving license data

---

**CONTACT:**

Ahmed Adam | Email: am4ma@hotmail.com
