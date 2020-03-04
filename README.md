# Kaggle Medical No Show data analysis

This Github repo contains a Juypter Notebook that does an analysis of medical appointment no-show data and derives useful insights on the various patterns in the patient behaviour for no-show. It also contains multiple predictive models for identifying if an appointment would be missed in the future.

You can read more about this in the below link

Medium Post - https://medium.com/@kamini.kadiresan/predict-top-5-insights-in-medical-appointments-no-show-using-data-science-e6763967c5d1?sk=92aea4abdecb947487d31a879632cb41

# Motivation

Wanted to take a new dataset that can be used to apply my skills learnt so far in my Data Scientist Nanodegree course at Udacity.
This dataset was specifically chosen because of my curiosity towards finding out why/who misses a medical appointment after booking it. The Kaggle dataset columns were intriguing to me and I felt there is some scope in creating my own new feature columns based out of the given data.  

# Libraries Used

Using pip install all the below libraries if they are not present already in your environment.
* pandas
* numpy
* matplotlib.pyplot
* matplotlib.ticker
* sklearn
* seaborn

# Data Used
Kaggle Data - https://www.kaggle.com/joniarroba/noshowappointments

# Files

* Medical_Appointments_NoShow_Analysis.ipynb 
The Jupyter notebook with complete analysis of the medical no-show data taken from Kaggle

* KaggleV2-May-2016.csv
The Kaggle dataset used for the analysis

# Summary
Based on the various patterns and trends analyzed for identifying the impact on no-show, we can conclude the following for each question.

1. Gender and Appointments
   1. Both genders missed the same amount of time the appointments (20%)
   2. Females took more appointment than Males
2. How Days of the week affect Appointments?
   1. The clinic is closed on Sunday
   2. There is way too less number of appointments handled on Saturday — which leads to infer them could be emergency cases
   3. No-show appointments seem to be consistent across Monday to Friday at 19%-21%.
   4. The busiest days for appointments are Tuesday & Wednesday followed by Monday
3. Did the SMS Reminders help reduce the No-Show?
   1. No, actually 28% of people who received one or more reminders missed the actual appointment against 17% of people who never received the reminder
4. Which Age group is better at keeping appointments — Seniors or Kids or Adults?
   1. Senior people are the most to keep up the appointments (84%)
   2. Adolescents are the least to keep up the appointments (74%)
   3. Also out of the 110K people, Adults (36K) and Young Adults (28K) are the most prominent age groups for medical appointments.
5. Does Booking in Advance make people miss the appointment?
   1. Any appointments booked 7+ days in advance had 31.5% miss rate!

# Acknowledgement

[JoniHoppen](https://www.kaggle.com/joniarroba) - For the Kaggle dataset

# License - 
Kaggle data is covered by its original license by its author.

The data analysis code (Juypter notebook) is released under MIT license.

Copyright (c) Kadiresan Dhanasekaran 
