# Data Visualization Project

## Data

The data I have decided to visualize comes from the Center for Disease Control (CDC) dataset, consisting of a random sample of 10,000 data points describing the general healht of an individual.  
I have created various interactive histograms and scatterplots of the data that look at the most predictive variables of the data--namely age and weight --for the different general health statuses. An interesting way I have incorporated weight and height into the visualization is through calculating the Body Mass Index (BMI) of an  individual and plotting this for different ages. I have also created some interactive visualizations involving BMI where I can toggle between Male and Females as well as display the BMI for different general health statuses.
Data Link: [CDC Dataset](https://gist.github.com/ridhimasaxena/a45f4774ff99a80bb5f71ca575f64ec3 "CDC Dataset")

## Visualizations

# Scatterplots

Below are scatterplots that I have created.  

Age (in years) on the x-axis vs Weight (in lbs) on the y-axis

[![image](https://github.com/ridhimasaxena/dataviz-project-template-proposal/blob/master/agevsweight.png)](https://vizhub.com/ridhimasaxena/ce31146b95a5497d96ec57e0670ff732)


Exercise habits in the past 30 days (0 for no, 1 for yes) on the x-axis vs weight (in lbs) on the y-axis
[![image](https://github.com/ridhimasaxena/dataviz-project-template-proposal/blob/master/exerciseandweight.png)](https://vizhub.com/ridhimasaxena/b8bbdb49bb93485d97c8c1f011615c3a)

Age (in years) vs. Weight (in lbs) for males and females.
[![image](https://github.com/ridhimasaxena/dataviz-project-template-proposal/blob/master/AgeVsWeightMF.png)] 
(https://vizhub.com/ridhimasaxena/1ed5e04673d1404e99489272bb952d0d?file=index.js)

A scatterplot describing BMI vs. Age for males and females.
[![image](https://github.com/ridhimasaxena/Data-Visualization-Project-Proposal/blob/master/BMIvsAge.png)] 

An interactive scatterplot describing weight vs. general health status. This scatterplot is one where you are able to decide the axes from a drop down and watch the scatterplot animate. 
[![image](https://github.com/ridhimasaxena/Data-Visualization-Project-Proposal/blob/master/GenHealthWeight.png)] 


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which variable out of all the variables in the dataset is the strongest indicator of general health?
Through analyzing the data using a random forest as well as ordinal logistic regression, I can report that age is the strongest indicator of general health followed by weight. 

[![image](https://github.com/ridhimasaxena/Data-Visualization-Project-Proposal/blob/master/RandomForestResults.png)] 

 * How can we plot body mass index?
Because age and weight are the two strongest indicators of general health, body mass index is appropriately plotted against age as seen in the above screenshot in the form of a scatterplot. This would also be interesting to see in a histogram. 

 * Do we notice any differences in the attributes for people with different general health statuses?
 * How does the general health compare for males vs. females?
 * How does the smoking compare for males vs. females?


## Sketches

[![image](https://github.com/ridhimasaxena/dataviz-project-template-proposal/blob/master/Cdc_Sketch.png)]
[![image](https://github.com/ridhimasaxena/dataviz-project-template-proposal/blob/master/SmokingStatusGender.png)]
[![image](https://github.com/ridhimasaxena/Data-Visualization-Project-Proposal/blob/master/BMIByAge.png)] 

The sketches above show the distribution of the dataset and the classifications of their general health status. The data is visualized in a pie chart. The next sketch compares general health between males and females in a bar chart. This satisfies the third question of how general health compares for males vs. females. Similarly the third sketch outlines smoking status between males and females. The last sketch outlines how to plot Body Mass Index. 


## Open Questions

I am still working on how to visualize the strongest variable to detect general health and how to categorize general health based on that variable. I think potentially using a regression model and then visualizing what that variable looks like would be useful. 

**I decided to use a random forest to determine this**

## Schedule of Deliverables

 * ~~Create a regression model in R to understand the most significant variable (2 days, 11/17)~~
   * ~~Determine which visualization would be the most powerful for showcasing this variable (11/17)~~
 * Create a violin plot (1 day, 11/18)
 * Create a ridge plot (1 day, 11/19)
 * ~~Create a scatterplot of Body Mass Index (3 days, 11/22)~~
   * Add a drop down menu to look at BMI for different health statuses (1 day 11/21)
   * Add a drop down menu to look at BMI for different genders (11/21)
 * Create a visualization to look at Body Mass Index for both Males and Females separated by color (1 day, 11/22)
 * Create a pie chart of the different health statuses (1 day, 11/23)
 * Plot general health for males vs females in a bar chart (1 day, 11/24)
 * Plot smoking status for males vs females in a bar chart (1 day, 11/24)
 * Plot smoking for different health statuses (2 days, 11/26)
 * Plot exercise for different health statuses (2 days, 11/26)
 * Plot weight for different health statuses (2 days, 11/26)
 * Divide weight/weight_desire and plot this metric for different health statuses (2 days, 11/28)
 * Decide which visualizations are the most interesting and meaningful (2 days, 11/30)
 * Refine all visualizations for submission (2 days, 12/2)
 * Buffer Period in case I am behind schedule (6 days, 12/8)
 * Create a template of the final project submission (7 days, 12/9)
 * Submit Final Project (12/9)
 
