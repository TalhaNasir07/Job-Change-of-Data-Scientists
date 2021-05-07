This is an attempt to predict which Data Scientist is going to move to a new job

The aug_train and aug_test files were obtained from kaggle: https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists

A description of how the process went can be read on this blog: https://medium.com/p/556ed2ccaeb2/edit

Features:

enrollee_id : Unique ID for candidate

city: City code

city_ development _index : Developement index of the city (scaled)

gender: Gender of candidate

relevent_experience: Relevant experience of candidate

enrolled_university: Type of University course enrolled if any

education_level: Education level of candidate

major_discipline :Education major discipline of candidate

experience: Candidate total experience in years

company_size: No of employees in current employer's company

company_type : Type of current employer

lastnewjob: Difference in years between previous job and current job

training_hours: training hours completed

target: 0 – Not looking for job change, 1 – Looking for a job change

