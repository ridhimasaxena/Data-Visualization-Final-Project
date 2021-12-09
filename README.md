# Data Visualization Project

## Data

The data I have decided to visualize comes from the Center for Disease Control (CDC) dataset, consisting of a random sample of 10,000 data points describing the general healht of an individual.  
I have created various interactive scatterplots, histograms, and bar charts of the data that look at the most predictive variables of the data--namely age and weight --for the different general health statuses. An interesting way I have incorporated weight and height into the visualization is through calculating the Body Mass Index (BMI) of an  individual and plotting this for different ages. I have also created some interactive visualizations involving BMI where I can toggle between Male and Females as well as display the BMI for different general health statuses. Lastly, the weight/weight desire ratio provides an insight on the individuals' goals or motivations for reaching a certain weight based on their target demographic. 
Data Link: [CDC Dataset](https://gist.github.com/ridhimasaxena/a45f4774ff99a80bb5f71ca575f64ec3 "CDC Dataset")

## Visualizations

### Scatterplots

Below are scatterplots that I have created.  

Age (in years) on the x-axis vs Weight (in lbs) on the y-axis

[![image](https://github.com/ridhimasaxena/dataviz-project-template-proposal/blob/master/agevsweight.png)](https://vizhub.com/ridhimasaxena/ce31146b95a5497d96ec57e0670ff732)


Exercise habits in the past 30 days (0 for no, 1 for yes) on the x-axis vs weight (in lbs) on the y-axis

[![image](https://github.com/ridhimasaxena/dataviz-project-template-proposal/blob/master/exerciseandweight.png)](https://vizhub.com/ridhimasaxena/b8bbdb49bb93485d97c8c1f011615c3a)

Age (in years) vs. Weight (in lbs) for males and females.

[![image](https://github.com/ridhimasaxena/Data-Visualization-Project-Proposal/blob/master/AgeVsWeightMF.png)](https://vizhub.com/ridhimasaxena/1ed5e04673d1404e99489272bb952d0d?file=index.js)

Age (in years) vs. BMI for males and females.

[![image](https://github.com/ridhimasaxena/Data-Visualization-Project-Proposal/blob/master/BMIvsAge_Updated.png)](https://vizhub.com/ridhimasaxena/23b7d479ee634e768b90dd3beb39784c?edit=files)

Interactively describing Weight (in lbs) vs. General Health status. This scatterplot is one where you are able to decide the axes from a drop down and watch the scatterplot animate. 

[![image](https://github.com/ridhimasaxena/Data-Visualization-Project-Proposal/blob/master/GenHealthWeight.png)](https://vizhub.com/ridhimasaxena/fae2b6a65fd347d8a2022765bb55afbe?edit=files)

Weight/weight desire ratio against Age

[![image](https://github.com/ridhimasaxena/Data-Visualization-Project-Proposal/blob/master/WeightbyDesiredWeight.png)](https://vizhub.com/ridhimasaxena/3ab2a629c01a4a2eac6136f9f9c37e58?edit=files)

Age (in years) vs. BMI for Different Health Statuses.

[![image](https://github.com/ridhimasaxena/Data-Visualization-Final-Project/blob/master/BMI_HealthStatus.png)](https://vizhub.com/ridhimasaxena/2b07073be0b34036bbde1a5d063934c8?edit=files&file=index.js)

### Histograms

Age (in years) vs. BMI for various age bands

[![image](https://github.com/ridhimasaxena/Data-Visualization-Project-Proposal/blob/master/Hist_BMI_Age.png)](https://vizhub.com/ridhimasaxena/b6cfe11d312d40e08da9d2568cc78406)

Age (in years) vs. BMI for various age bands using brushing

[![image](https://github.com/ridhimasaxena/Data-Visualization-Project-Proposal/blob/master/Hist_Brushing.png)](https://vizhub.com/ridhimasaxena/bced0f0db29a47c394c792bd01185bc0)


### Bar Charts

General Health vs Weight

[![image](https://github.com/ridhimasaxena/Data-Visualization-Project-Proposal/blob/master/GenlHealthvsWeight.png)](https://vizhub.com/ridhimasaxena/165aa99452b747878e817154ac9ff525?edit=files&file=index.js)

## Questions & Tasks

The following tasks and questions have driven the visualization and interaction decisions for this project:

 * Which variable out of all the variables in the dataset is the strongest indicator of general health?


Through analyzing the data using a random forest as well as ordinal logistic regression, I can report that age is the strongest indicator of general health followed by weight. 

[![image](https://github.com/ridhimasaxena/Data-Visualization-Project-Proposal/blob/master/RandomForestResults.png)] 

 * How can we plot body mass index?


Because age and weight are the two strongest indicators of general health, body mass index is appropriately plotted against age as seen in the above screenshot in the form of a scatterplot. This is also interesting to visualize in a histogram. 

 * Do we notice any differences in the attributes for people with different general health statuses?

Yes, we notice that  people in the "fair" health status category tend to be the individuals with the highest weight and subsequent BMI. This is interesting because we would hypothesize that "poor" health would have the highest BMI. We also notice that there isn't too much of a pattern for the age of people in every health status. There are many individuals of all ages in every category of health. However, we do notice that there are very few people in the "excellent" health status who are over age 75 and very few people in the "very good" status who are over age 80. This may also be because there are less individuals above those ages in the dataset itself. Similarly, exercise vs no exercise as well as smoking status did not have much of an impact on weight or health status. 


## Sketches

[![image](https://github.com/ridhimasaxena/dataviz-project-template-proposal/blob/master/Cdc_Sketch.png)]
[![image](https://github.com/ridhimasaxena/Data-Visualization-Project-Proposal/blob/master/BMIByAge.png)] 

The sketches above show the distribution of the dataset and the classifications of their general health status. The data is visualized in a pie chart. The next sketch compares general health between males and females in a bar chart. This satisfies the third question of how general health compares for males vs. females. Similarly the third sketch outlines smoking status between males and females. The last sketch outlines how to plot Body Mass Index. 


## Schedule of Deliverables

 * ~~Create a regression model in R to understand the most significant variable (2 days, 11/17)~~
   * ~~Determine which visualization would be the most powerful for showcasing this variable (11/17)~~
 * ~~Create a scatterplot of Body Mass Index (3 days, 11/22)~~
   * Add a drop down menu to look at BMI for different health statuses (1 day 11/21)
   * Add a drop down menu to look at BMI for different genders (11/21)
 * Create a pie chart of the different health statuses (1 day, 11/23)
 * Plot weight for different health statuses (1 day, 11/24)
 * Plot smoking status for males vs females in a bar chart (1 day, 11/24)
 * Plot smoking for different health statuses (2 days, 11/26)
 * Plot exercise for different health statuses (2 days, 11/26)
 * Plot weight for different health statuses (2 days, 11/26)
 * ~~Divide weight/weight_desire and plot this metric for different ages (2 days, 11/28)~~
 * ~~Decide which visualizations are the most interesting and meaningful (2 days, 11/30)~~
 * Refine all visualizations for submission (2 days, 12/2)
 * Buffer Period in case I am behind schedule (6 days, 12/8)
 * Create a template of the final project submission (7 days, 12/9)
 * Submit Final Project (12/9)
 

## Future Exploration
