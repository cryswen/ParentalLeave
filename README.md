
# ParentalLeave

This project is to discuss the parental leave policies from more than 200 universities in US and Canada and compare it with companies in different area. 

## Motivation

My motivation for this project comes from the fact that as a graduate student, I had gone through the process of having a child and have to consult for parental leave policies. By looking up parental leave policies at different places, I think it's important to let the pubic aware of the huge difference between academia and industry in parental leave policies and that the policy can be improved in multiple ways. 

## Datasets

The datasets I used include:

A recent study of parental leave policies of 205 universities by a group from University of Colorado at Boulder and the Santa Fe Institute: the 'parental_leave_policies.csv' file from https://github.com/aaronclauset/parental-leave.

An coordinates data for these universities obtained from Google Geocode API.

A summary table of parental leave policies scraped from website: https://fairygodboss.com/maternity-leave-resource-center.

## Preliminary analysis
### Geographic Distribution of Parental Leave at Universities
To evaluate how geography affect different university policies, I plot the average and difference (between men and women) length of paid leave weeks on a map with color scales.

![alt text](https://github.com/cryswen/ParentalLeave/blob/master/figures/geo_dist.png)
![alt text](https://github.com/cryswen/ParentalLeave/blob/master/figures/geo_sex_dist.png)

I find that the geographic distribution of universities have some effect on the parental leave policies. Through careful inspection of the figure, it is significant only a small portion of universities have long (>20) weeks paid parental leave and they are more likely to be in Canada and the costal area of US with few in central US.

### Group comparisons
#### Private vs. Public Universities
