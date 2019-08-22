# capstone_project_2
###################### EXECUTIVE SUMMARY #############################

Situation: The Consumer Financial Protection Bureau has begun publishing a survey that aims to map the Financial Well-Being of it's participants. The survey has a wide range of questions pertaining to financial literacy and self-assessment regarding financial choices and plans. The goal is to give people the tools to make better financial decisions to improve their financial well-being. 
Problem: The CFPB releases this data for analysis to the public in order to find any insights. The biggest issue is the dataset is rather large with over 200 variables that cover a wide range of topics. It is difficult to find correlations in the data that are not overgeneralizations that will not scale to new data. 
Solution: It is important to tackle this dataset with a clear goal in mind. It would not make sense to analyze every variable in the prospect of finding some underlying pattern. It is best group the variables as closely correlated as possible, compare them against each other and the target variable, then extrapolate which of those variables have the greatest impact on financial literacy. 
Evaluation: The OLS model has a accurate score of 95% on the test data after feature selection. Other models didn't score as well but that may be an issue with the parameters for each. Ridge isn't necessarily for regression but more statistical analysis. Further study could greatly improve the robustness of the model when one considers the other variables that were not included. 
Recommendations: Develop a user interface to encourage all walks of life to participate in the survey. The more people that use the survey the more data is accrued over time and thus allowing researchers to monitor changes in financial well-being over time. The CFPB is an excellent resource for financial literacy; their resources could be implemenented into this project as a followthrough after the survey and analysis of users' results. 

### Reference Documents ###
This project has three documents that are used to explain the variables and research methodology behind the Consumer Financial Protection Beareau Financial Well-Being Survey. These documents will be cited throughout the project. They are in this repository. The three documents are as follows: 

1. National Financial Well-Being Survey Public Use File Codebook: Explains the meanings of the different variables along with summary statistics

2. National Financial Well-Being Survey Public Use File User’s Guide: Explains how to use the available data and the scaling and scoring involved in making the results as accurate as possible. 

3. CFPB Financial Well-Being Scale Scale development technical report: Explains the technical definitions of Financial Well-Being and how the questions and surveys were selected based on these definitions. 

