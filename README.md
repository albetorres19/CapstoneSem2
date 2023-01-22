# Semester 2 Capstone Project - Income Predictor

## Pitch
 * Business Problem
      * For this project I wanted to build a model that colleges can show potential college students how likely they are to make over 50K
      a year if they decided to pursue a college education.  
       
 * Business Solution
      * College can recommend going to college will allow students to make more than 50K a year than those people that do not 
      go to college.
      * Having a bachelors can put you over 50K a year faster rather than those who have a High School education.


![image](https://www.ischool.berkeley.edu/sites/default/files/styles/fullscreen/public/sproject_teaser_image/screen_shot_2020-12-07_at_15.43.34_copy.jpg?itok=IDSSEGe1)

## Authors
 * Alberto Torres




## Business Understanding
  * College enrollment are slowly declining throughout the United States. College's can use this model to show potential students
  how more likely they are to make more than 50K a year if they pursue a college education. They can show that the median income in the United States currently of High School graduates that do not go to college falls around 40K. 
    
 
## Data Understanding and Analysis
   * Source of data
     * [Income Dataset](https://www.kaggle.com/datasets/mastmustu/income)
    
   * Description of data & Features used
     * Income Dataset
       * Target Variable: Income >50K
       * education: Highest level of education individual achieved
       * occupation: Current work position
       * race
       * gender: Male or Female
       * relationship: If individual is a husband, wife, single, etc.
       * Hours worked per week
    

     
     
   *(Figure 1)* Demonstration of people who make over 50K a year sorted by education

![image](https://user-images.githubusercontent.com/110133652/213798773-248e6906-4341-4e4b-9fbd-a8fe92375c4a.png)

   *(Figure 2)* Demonstration of people who make less than 50K a year sorted by education
   
![image](https://user-images.githubusercontent.com/110133652/213937408-0cc3725d-5715-4164-976f-290e30d9a601.png)


   *(Figure 3)* Visualizing comparison how many individuals make or 50K(1) and how many make less than 50K(0).
   
   ![image](https://user-images.githubusercontent.com/110133652/213937334-c211bcb4-ea8a-4d8f-9bfd-fbab70179429.png)

   *(Figure 4)* Visualizing the decision tree and showing how it is branching to make a decision.
   
   ![image](https://user-images.githubusercontent.com/110133652/213800364-6b3d3596-ffa4-414d-b258-91869d449999.png)
 
   
       
## Models and Evalution
   For this project 2 models were used: Decision Tree and Random Forest. The main model I would take to production
   would be my Random Forest model. For my baseline model for my Random Forest I am mostly looking at recall and percision    as the metric of most importance. The baseline recall and precision of the model for individuals who made less than 50K    was 71% for recall and 94% for precision, for those who made over 50K recall was 85% and precision was 49%. After doing    a gridsearch to optimize the model, recall for those who make less than 50K went up to 73% and precision stayed at 94%.    For those who make more than 50K recall stayed the same at 85% and precision went up to 51%
   

## Conclusion
   * This model is recommend to be used based on the precision and recall the model is producing for individuals that are
     weighing their options on whether getting a college education because the of income they will be earning after
     they obtain their degree/education.

## Repository Navigation

     *All files and notebook for repo are on the main branch with no folders, it is designed this way for easy access.
     As well, the repo does not contain many files or multiple notebook, so navigation is straightforward.  

See the full analysis in the [Jupyter Notebook](https://github.com/albetorres19/CapstoneSem2/blob/main/index.ipynb) or review this [presentation](./presentation.pdf).

Link to our repository: [https://github.com/jaeminlee95/Semester1_Capstone_Group_3](https://github.com/albetorres19/CapstoneSem2)
