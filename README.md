# Projet Final 

## CSI 4142:  Fundamentals of Data Science
winter 2023

### Group members : 
Souleymane Wilfried Sankara, #300100940
Marie Fabienne Sawadogo; #300101795
Tata Saidatou Berte,  #300100935

# Data set description
Link to our data set : 
-  https://www.kaggle.com/datasets/thedevastator/jobs-dataset-from-glassdoor


# 1-Definition of the grain

In the context of dimensional modelling, the grain of a fact table refers to the level of detail or granularity of the data in the table. The grain determines the lowest level at which the data in the fact table can be analyzed and aggregated.
In this instance, the grain is the average salary for data scientist positions according to their company and location.




# 2-Dimensional, dimension attributes and measures/facts

We will have 3  dimensional tables : Location dimension , Company dimension, Job dimension.<br>
What we want to track in our database is the evolution of the salary range corresponding to a data scientist job type in the companies. 

#### Dimensions : <br>



Job Title : <br>
   |Job ID (PK)| Integer| sample value :2| 
  | Job Title| String| sample value Data Science Manager|
   Job Classification: String, sample value: Data scientist, data engineer

Location dimension :
 
 Location ID (PK)
 City : String , sample value : Houston
State : String, sample value : TX

Company dimension :

 Company ID(PK)
 Name: String, sample value: Apple
 Size: Integer Range, sample value: 501-1000 (employees)
 Rating: Integer, sample value: 4.5 (over 5)
Type of ownership: String, sample value: Company -private
Industry: String , sample value: Aerospace & Defense
