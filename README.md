# Car_Fuel_Efficiency_Prediction-

### Project Introduction: 
This is my first "serious" project, where I applied more advanced concepts in traditional ML to solve a regression problem:
- The EDA digs deeper, considering different relationships and scenarios to better understand the data behavior 
- I built more **advanced models** compared with my previous project where I just did a multiple linear regression: decision trees and random forests
- I used **feature selection** based on a **model-agnostic** analysis and also did take into consideration **model-based numbers**
- I did **hyper parameter tuning** and **cross-validations**
- All decisions were based on a careful thought process, taking in considerations different variables in a **integration process***: the insights found during EDA, the information obtained during the models training, the machine learning fundamental principles, what were the stakeholders requests and my judgement on each topic.
- Technologies used: Python analysis libraries (pandas, numpy), graphical libraries(Matplotlib and Searborn), Scikit-learn machine learning modules 

This project was built using the public dataset: UCI Auto MPG dataset. You can find it here:https://archive.ics.uci.edu/dataset/9/auto-mpg

### Problem Context: 
A car manufacturer by the name UCI, wants to understand which vehicle characteristics influence fuel efficiency. Your goal is to build a regression model that predicts the MPG of a vehicle from its technical specifications. **Prediction accuracy alone is not enough**. 
The company also wants clear answers to the following questions:
• Which variables have the greatest influence on fuel efficiency?
• Can some variables be removed without significantly affecting performance?
• Which regression algorithm offers the best balance of predictive performance and interpretability?

### Initial Data Structure: 
The dataset contains 398 vehicle records. The prediction target is MPG (miles per gallon). UCI identifies seven predictive features, while car_name is an identifier that should be evaluated carefully.
The data isn't completely clean, which required some inspection and clean before moving to the EDA step.
The full initial dataset can be found in the "Data.xlsx" file
##### Note: I'm aware that this a small dataset, but everything that was made, namely all the applied thought processes could be used in any dimension dataset. 

### Presentation:
I have a 4 pages word report in the repository that contains all the workflow, the main decisions I took during the project and a good resume of the notebook. Please read the document for further context and understand. 




