# Healthcare-dot-Gov-Notebooks
This repo houses visualizations, exploratory analysis, and models from healthcare.gov data. 

[2017 Individual Dental Insurance Market Analysis](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks/blob/master/README.md#dental-insurance-premiums)<br>
[2017 Individual Medical Insurance Market Analysis](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks#individual-medical-insurance-premiums)<br>

# Dental Insurance Premiums

These charts come from analysis of the [2017 QHP Landscape Individual Market Dental dataset](https://data.healthcare.gov/dataset/2017-QHP-Landscape-Individual-Market-Dental/gwq7-ribq). 

## State Premiums

First, we can take a look at premiums by state. Note that the healthcare.gov data comes from the Federal exchanges and thus do not include several states which set up their own exchanges (e.g. California). 

![Average Dental Insurance Premiums by State](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks/blob/master/Images/dental_map001.svg)

If we want a more detailed look at the state data, the bar chart below lays out all the state data in a more quantitative format. 

![Average Dental Insurance Premiums by State - Bar Chart](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks/blob/master/Images/dental_state001.svg)

We can also break the state data down further by county. Note that there seem to be few major differences within states, with a some exceptions. 

![Average Dental Insurance Premiums by County](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks/blob/master/Images/dental_map002.svg)

For instance, the Las Vegas metro area appears to have less expensive dental insurance options than northern Nevada. It also appears that eastern and central North Carolina have cheaper options than the more rural western / Appalachian region of North Carolina. Similarly, western Oregon and its metro areas along the I-5 corridor (Portland, Eugene, Salem) have lower monthly premiums than the more rural / mountainous portions of the state in the East. 

## Issuers

This chart shows the average monthly premium for the top 20 dental insurance issuers. 

![Average Dental Insurance Premiums by Issuer](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks/blob/master/Images/dental_issuer002.svg)

We can see Dominion and Humana offer some of the least expensive plans. However, this should be taken with the caveat that this data does not factor in which states / localities these insurers operate in. Nor does it examine quality of coverage. 

## Population Density

Population density appears to play a slight role in premiums. States with higher population densities tend to have lower premiums. At the extreme, we can see states like Alaska (which has the lowest popuulation density) have significantly higher premiums. 

![Average Montly Dental Premiums by Population Density](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks/blob/master/Images/dental_pop_den001.svg)


# Individual Medical Insurance Premiums


![Average Medical Insurance Premiums by State](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks/blob/master/Images/medical_map001.svg)

![Average Medical Insurance Premiums by County](https://github.com/hjhuney/Healthcare-dot-Gov-Notebooks/blob/master/Images/medical_map002.svg)




# Other State Data

[Master List - Other State Exchanges](https://www.healthcare.gov/marketplace-in-your-state/)<br>
[Covered California](https://hbex.coveredca.com/data-research/)<br>
