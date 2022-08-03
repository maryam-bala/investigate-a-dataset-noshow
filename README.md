# Project: Investigate  a Dataset: No-show appointments Dataset in Brazil

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment.The data is sourced from Kaggle. It can be found [here](https://www.kaggle.com/datasets/joniarroba/noshowappointments) A number of characteristics about the patient are included in each row. The variables of the dataset are :

|Column      | Description |
| :---       | :---: |
|PatientID            |	Identification number of a patient
|AppointmentID        | Identification number appointments
|Gender	              | Male or Female
|ScheduledDay | The day an appointment scheduled
|AppointmentDay | The day of the appointment 
|Age | How old the patient is
|Neighbourhood |Location of appointment
|Scholarship | True of False
|Hipertension | True or False
|Diabetes | True or False
|Alcoholism | True or False
|Handcap | How many disabilities the patient has 
|SMS_received |  True or False
|No-show | Yes or No - ***'Yes'*** indicates patients did not show up while ***'No'*** indicates show up


**Scholarship, Hipertention, Diabetes, Alcoholism, and SMS_received are binary fields ( 0 or 1) - signifying True or False.** 

The Dataset will be analysed to find out the factors that determine whether a patient shows up for their appointment or not. 

***QUESTIONS TO ANSWER***
1. What age group misses the appointment the most ?
2. Are people with scholarship more or less likely to miss appointments ?
3. Which gender shows up for their appointment more ?
4. Do people that receive SMS miss appointments ?
5. Which day of the week is associated with the most No-shows ? 
