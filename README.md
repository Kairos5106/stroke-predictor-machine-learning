# MLTeam44

Created a pre-processing Pandas python code to process our stroke csv file. I firstly converted categorical columns into numerical values then 
replace the missing values using imputation mean method. I also created another new column called 'diabetes_status' which categorizes individuals 
in numerical weightage based on their 'avg_glucose_lvl' which below 140 is considered normal, 140 to 199 considered as pre-diabetic and 200 and above as
diabetic patient. Information above was referred based on CDC https://www.cdc.gov/diabetes/basics/getting-tested.html#:~:text=A%20fasting%20blood%20sugar%20level,higher%20indicates%20you%20have%20diabetes.
At the moment, i only found that 'smoking_status' and 'bmi' columns had missing values. I did not include cross validation in this processing data. 
