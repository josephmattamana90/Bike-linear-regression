# Bike sharing linear regression
> This project aims to find the variables that are significant in predicting the demand for shared bikes and how well those variables describe the bike demand.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- The dataset is about a US bike-sharing provider BoomBikes that has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- We have used linear regression to understand the variables that are influencing the demand of the bikes.
- There are 2 models which have been built. First model has the 'mnth' variable which has been encoded to dummy variables, and the second model has derived variable 'qrtr' from the 'mnth' variable.
- On evaluating the 2 models, the first model has better r2.



## Conclusions
- The first model has better R2 score compared to the second model. 
- The top 3 features contributing significantly towards explaining the demand of shared bikes are 
as follows:
   • temp (coeff 0.5301): Indicates that a unit increase in the variables ‘temp’ causes increase in 
     demand by 0.5301.
   • yr (coeff 0.2292): Indicates that a unit increase in the variables ‘temp’ causes increase in 
     demand by 0.2292.
   • weathersit_3 (coeff -0.2486): Indicates that a unit increase in the variables ‘weathersit_3’
     causes decrease in demand by 0.2486.



## Technologies Used
- Pandas - Version 1.5.3
- Matplotlib - Version 3.7.1
- Seaborn - Version 0.12.2
- statsmodels
- sklearn



## Acknowledgements
Give credit here.
- This project has been developed as part of Upgrad IIITB programme for AI and ML course's case study


## Contact
Created by [@josephmattamana90] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->