# Projet Final 

## CSI 4142:  Fundamentals of Data Science
winter 2023



### Group members : 
Souleymane Wilfried Sankara, #300100940 <br>
Marie Fabienne Sawadogo; #300101795  <br>
Tata Saidatou Berte,  #300100935 <br>

# Data set description
Link to our data set : 
-  https://www.kaggle.com/datasets/thedevastator/jobs-dataset-from-glassdoor


# 1-Definition of the grain

In the context of dimensional modelling, the grain of a fact table refers to the level of detail or granularity of the data in the table. The grain determines the lowest level at which the data in the fact table can be analyzed and aggregated. <br>
In this instance, the grain is the average salary for data scientist positions according to their company and location.



# 2-Dimensional, dimension attributes and measures/facts

We will have 3  dimensional tables : Location dimension , Company dimension, Job dimension.<br>
What we want to track in our database is the evolution of the salary range corresponding to a data scientist job type in the companies. 

#### Dimensions : <br>



`Job Title : <br>
   Job ID (PK), Integer, sample value :2  <br>
    Job Title ,String, Sample value Data Science Manager <br>
   Job Classification: String, sample value: Data scientist, data engineer` <br>

Location dimension :
 
` Location ID (PK)  <br>
 City : String , sample value : Houston  <br>
State : String, sample value : TX` <br>

Company dimension :

` Company ID(PK)
 Name: String, sample value: Apple  <br>
 Size: Integer Range, sample value: 501-1000 (employees) <br>
 Rating: Integer, sample value: 4.5 (over 5) <br>
Type of ownership: String, sample value: Company -private <br>
Industry: String , sample value: Aerospace & Defense` <br>


# 3- Dimensional model
![alt text](https://github.com/fabienne-lab/CSI-4142/blob/images/image.jpg?raw=true)
