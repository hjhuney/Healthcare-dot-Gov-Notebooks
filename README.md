# Healthcare-dot-Gov-Notebooks
This repo houses visualizations, exploratory analysis, and models from healthcare.gov data. 


# Dental Insurance Premiums

These charts come from analysis of the [2017 QHP Landscape Individual Market Dental dataset](https://data.healthcare.gov/dataset/2017-QHP-Landscape-Individual-Market-Dental/gwq7-ribq). 

## State Premiums

First, we can take a look at premiums by state. Note that the healthcare.gov data comes from the Federal exchanges and thus do not include several states which set up their own exchanges (e.g. California). 

![Average Dental Insurance Premiums by State](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks/blob/master/Images/dental_map001.svg)

If we want a more detailed look at the state data, the bar chart below lays out all the state data in a more quantative format. 

![Average Dental Insurance Premiums by State - Bar Chart](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks/blob/master/Images/dental_state001.svg)

We can also break the state data down further by county. Note that there seem to be few major differences within states, with a few exceptions. 

![Average Dental Insurance Premiums by County](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks/blob/master/Images/dental_map002.svg)

For instance, the Las Vegas appears to have less expensive dental insurance options than the rest of Nevada. It also appears that eastern and central North Carolina has cheaper options than western North Carolina. 

## Issuers

![Average Dental Insurance Premiums by Issuer](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks/blob/master/Images/dental_issuer001.jpg)

## Population Density

Population density appears to play a slight role in premiums. States with higher population densities tend to have lower premiums. At the extreme, we can see states like Alaska (which has the lowest popuulation density) have significantly higher premiums. 

![Average Montly Dental Premiums by Population Density](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks/blob/master/Images/dental_pop_den001.svg)

