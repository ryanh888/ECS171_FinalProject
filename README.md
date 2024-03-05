## ML Project Write Up - Predictors of Academic Success
#### Justin Yan, Ryan Hua, Sahil Khatri, Bao Hu

For our ML Project, we decided to explore certain variables responsible for predicting academic success in a college setting. After scanning over the data set, we came to the conclusion that we wanted to use debtors, occupations of parents, and scholarship holders as the variables that best predict academic success. 

We chose the occupations of parents as the primary attribute because higher levels of education may have a substantial influence on children. This is related to academic success as it is somewhat reliant on income levels. For example, students with higher levels of income have greater access to tutors and academic resources, which boost academic performance. The model aims to make comparisons between students of lower and higher social strata, predicting their academic performance. When it comes to academic success, we were given the performance metrics of students from a university for the first two semesters, so based on their economic backgrounds, we’ll predict grades for both. 

The stress of debt can influence how well a student does well in school because of the potential need to partake in a part-time job lowering the amount of time they are able to commit towards academics. 

Scholarships provide students with financial support, possibly reducing the necessity to work solely to pay for school. It additionally can serve as motivation or a stressor for the student to perform well, as scholarships commonly will require a student to attain a certain GPA to continue receiving support. 

With the described variables, we will conduct exploratory data analysis to understand the relationships between them and a student’s academic success while describing patterns, correlation between variables, and potential outliers. We will determine the most significant factor in gauging academic success by utilizing regression analysis to build an accurate predictive model. Through methods learned in class, we will validate our model’s accuracy and reliability, ensuring it is not biased, and provides meaningful insight on how academic success is influenced by the selected variables. 


### Action Plan::
1. Complete/Observe the public data set variables and their values. Import the data onto your computer/take notes/make any observations that will help with EDA. `Feb 3rd/4th`
2. Calculate the descriptive statistics related to the chosen variables debtors, occupations, scholarship holders and the outcomes of how well each person with these variables is doing academically. Use python for this. `Feb 10th-11th`
3. Extrapolate the outcomes with these variables, and create a regression model (haven’t chosen what to use yet) to predict academic success based on this data. 
`Feb 20th`
4. Record the correlation between the variables if there are any . Test the performance of the model to check for underfitting or overfitting. 
`Feb 27th`
5. Once performance is assessed, integrate the model and predictions into a web-app. 
Decide on the visualizations of the data (box-plot, graph, scatter-plot). Highlight the outliers. Write descriptions of the model in the app.
`Until Due Date`
