# EpsilonAI_FinalProject

Title : Predicting Annual Salary of Software Developers.

Data Set : Data Set contains 83,000 Rows of Software Developers from 180 Country and 48 Columns ( Country , Specilization , Years of Experience,  Organization Size , 
           Ethnicity, Salary , ...)

Data Set Source  : Stackoverflow

Overview : This project predicts Annual Salary of Software Developers in United States Dollars based on many features such as Country , Years of Experience 
          , Specilization , Organization Size , Ethnicity , etc .. ). I started with exploring the data set by checking values of columns and Null values.
          Then started the cleaning process by dropping columns that aren't necessary , Dealing with Duplicates , Null Values , Changing names of values inside 
          columns to make more sense , Feature Engineering , Encoding. Then Performed Exploratory Data Analysis to find insights and answer few questions 
          about the data , and also to check for outliers if existed. After that I used     PyCaret     to find the best Machine Learning Model to be used with this Data 
          based on Root Mean Squarred Error and Mean Absolute Error.     Random Forest     For Regression Was Chosen and then I performed Hyperparameter Tuning to reach 
          maximum accuracy that I could in less than a week ( of course It wasn't the best ) My accuracy  70+% , 
          Of course its depeatable here in this project as it needs lots of time to collect real data from different countries based on specilizations 
          and years of experience for 180 Country) . Then I used       Pipeline       to Perform the Data Cleaning of the user data automatically then Joblib to 
          make it an importable file to be used in Visual Studio Code with         Flask         . Then Deployed the project Locally but not yet deployed on Heroku.      
