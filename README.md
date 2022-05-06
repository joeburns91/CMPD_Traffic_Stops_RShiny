# Charlotte Traffic Stops Data Visualization


## Data Source
Data is available at the [Charlotte Data Portal](https://data.charlottenc.gov/datasets/officer-traffic-stops/explore).

## Research Questions
1. What correlations can be uncovered through visual analytics 


### Create R Shiny App
R Shiny app to make the dataset easily accessible for anyone [here](https://jburns27.shinyapps.io/R_Shiny/). The app contains EDA insights for the dataset as well as comparing the location of the traffic stop to local population demographics and income. Source code and files for the R Project are located in R_Shiny folder to be able to run the app from Rstudio rather than going to the link provided. To do so,
- Download all items in the repository as a zip file by clicking 'Code' button above
- Unzip the downloaded foler
- Open the folder "R_Shiny"
- Open CMPD_Traffic_Stops_Shiny.R
- Click "Run App" in the top-right corner of the code panel


## Conclusions
We realize that by analyzing this dataset, we could shed light on a potentially controversial topic, that is, how the race/ethnicity/gender of the driver/officier can help to predict the outcome of a traffic stop. 

If this is a finding, it should not be used to guide police targeting, but rather to illuminate bias in traffic stops.  Note that being able to predict the outcome of a traffic stop based on race, ethnicity or gender is inherently unethical/discriminatory. Ideally, traffic stop outcomes based on these characteristics should be proportional to the demographic population of the area under observation.  

Regardless of our findings, we would like to be explicit about the fact that none of our findings are causal. Rather they shed light on correlations in the data that may be used to dismantle bias in policing. There could be a multitude of factors that correlate with race that cause the disparity of traffic stops. Discrimination can not be concluded as the sole factor. However the findings can help drive further investigation.
