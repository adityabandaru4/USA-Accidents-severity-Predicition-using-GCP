# knowledge-based-systems
<h1 align = "center">  </h1>

<br/>



## Team Name:

Team Members:<br/>
1)Aditya Bandaru<br/>
2)Anusha Balumuri<br/>
3)Ranga Sai Pavan Kiran Vipparla<br/>
4)Sandeep Bellary<br/>
5)Siri Chandana Sureddi<br/>

## Project Description 
- An accident is an uncontrollable incident which happens at times. So our project is focused on “ Car accidents in US” 
- This dataset has been collected in real-time, using multiple Traffic APIs. Currently, it contains accident data that are collected from February 2016 to December 2019 for the Contiguous United States.
- With this dataset we are going to predict the severity using factors such as day, weather, county, state, and various other factors.
- The main audience for this project is civilians and state traffic department. This may help them in containing those accidents..

### 1. Reasearch Question
Job boards can be host to scammers who are looking to defraud victims who are at their most suggestible and vulnerable 
that is, job seekers who are so eager to land a position that they ignore the warning signs that all is not as it seems.
Scammers know that finding a job can be tough. To trick people looking for honest work, scammers advertise where real employers 
and job placement firms do. They also make upbeat promises about your chances of employment, and virtually all of them 
ask you to pay them for their services before you get a job. 
<br> The major targets for the scammers are students. Colleges/Universities always explains the students the red flags regarding the 
employment oppurtunities. Still it is not hundered percent possible to eliminate all the scams or save students from scams all the time.
Therefore, we propose a solution to which helps to identify the fradulent jobs using text and meta data information modelling. <br>

### 2. Domain and Data: Data Description

#### A. Source and Size of Data
This is a countrywide car accident dataset, which covers 49 states of the United States. The accident data are collected from February 2016 to December 2019, using several data providers, including two APIs that provide streaming traffic incident data. These APIs broadcast traffic data captured by a variety of entities, such as the US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors within the road-networks. Currently, there are about 3.0 million accident records in this dataset.
- ID - This is a unique identifier of the accident record.
- Source - Indicates source of the accident report (i.e. the API which reported the accident.).
- TMC - A traffic accident may have a Traffic Message Channel (TMC) code which provides more detailed description of the event.
- Severity - Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic (i.e., short delay as a result of the accident) and 4 indicates a significant impact on traffic (i.e., long delay).
- Start_Time - Shows start time of the accident in local time zone.
- End_Time - Shows end time of the accident in local time zone.
- Distance(mi) - The length of the road extent affected by the accident.
- City - Shows the city in address field.
- County -Shows the county in address field.
- State - Shows the state in address field.
- Zipcode - Shows the zipcode in address field.
- Country - Shows the country in address field.
- Timezone - Shows timezone based on the location of the accident (eastern, central, etc.).
- Weather_Timestamp - Shows the time-stamp of weather observation record (in local time).
- Temperature(F) - Shows the temperature (in Fahrenheit).
- Wind_Chill(F) - Shows the wind chill (in Fahrenheit).
- Humidity(%) - Shows the humidity (in percentage).
- Pressure(in) - Shows the air pressure (in inches).
- Wind_Direction - Shows wind direction.
- Wind_Speed(mph) - Shows wind speed (in miles per hour).
- Precipitation(in) - Shows precipitation amount in inches, if there is any.
- Weather_Condition - Shows the weather condition (rain, snow, thunderstorm, fog, etc.).

#### B.Tentative plan for analysis on GCP

##### Explratory Data Analysis
- We use Cloud AutoML and will be exploring the data
- For each observation, important subsets are identified
- Interrelationships between various attributes will be observed
- Guessing for possible associations between target variable and predictors
- Looking for associations among the predictors
<br>

##### Preprocessing Phase
- We dig and explore for all the null values and missing values like ‘Number’, ‘End_Lng’, ‘End_Lat’ columns in the dataset.
- We will find and remove all the outliers in the dataset by looking all the columns and finding the values that are very different from the rest of them.
- We will look for various features to find the most relevant ones to use them for predictions like ‘Weather_Timestamp’, ‘Severity’ , etc., from the dataset.
- We will learn what are the columns that are least significant like ‘End_Lng’ and ‘End_Lat’ columns in the dataset and remove them.
- We will use Cloud Dataflow, Google Dataprep and Google Dataproc for cleaning the data and pre-processing the dataset

##### Dashboard for Users and Dashboard for Data Engineers
- A Dashboard is created for users.
- Users dashboard is included with action-oriented features as make it easier for them which will help them refer to or look at what they desire

##### GCP processing - ML


##### Evaluation of Results


##### Steps for production Model


##### Final Dashboard for User Group
- 


