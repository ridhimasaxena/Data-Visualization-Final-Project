# Data Visualization Project

## Data

The data I propose to visualize for my project is the Center for Disease Control (CDC) dataset that I have been analyzing for the past few months. I believe that there are interesting attributes in the dataset as well as many data points (10,000), which could lend to lots of potential for various visualizations.
I am looking to create different types of histograms of the data through violin plots or ridge plots. One interesting aspect about the data that I’d like to explore includes the Body Mass Index (BMI) of the individuals in the dataset. I would like to create some interactive visualizations involving BMI where I can toggle between Male and Females as well as display the BMI for different general health statuses.
Data Link: [CDC Dataset](https://gist.github.com/ridhimasaxena/a45f4774ff99a80bb5f71ca575f64ec3 "CDC Dataset")

## Prototypes

I’ve created a proof of concept prototype visualizations of this data. It's a scatterplot and it shows age (in years) on the x-axis and weight (in lbs) on the y-axis. 

[![image](https://github.com/ridhimasaxena/dataviz-project-template-proposal/blob/master/agevsweight.png)](https://vizhub.com/ridhimasaxena/ce31146b95a5497d96ec57e0670ff732)

Another visualization is a scatterplot showing whether a person exercises or not (0 or 1) on the x-axis and what their weight is on the y-axis. 
[![image](https://github.com/ridhimasaxena/dataviz-project-template-proposal/blob/master/exerciseandweight.png)](https://vizhub.com/ridhimasaxena/b8bbdb49bb93485d97c8c1f011615c3a)

A scatterplot describing age vs. weight for males and females.
[![image](https://github.com/ridhimasaxena/dataviz-project-template-proposal/blob/master/AgeVsWeightMF.png)] 



## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which variable out of all the variables in the dataset is the strongest indicator of general health?
 * How can we plot body mass index?
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



## Schedule of Deliverables

 * Create a regression model in R to understand the most significant variable (2 days, 11/17)
       **   Determine which visualization would be the most powerful for showcasing this variable (11/17)
 * Create a violin plot (1 day, 11/18)
 * Create a ridge plot (1 day, 11/19)
 * Create a scatterplot of Body Mass Index (3 days, 11/22)
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
 
