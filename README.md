# Employee_Database_challenge.sql

## Overview ##

The Purpose of the task is for us to see who is eligable for retirement. How do we know who is eligable? First we look at the ages of the employees, so the employees have to be a certain age to qualify for the retirement, so we put a date range to see who is with in that range. The next requirement is to see if the employee has been working with the company long enough. 

![retirement info3](https://user-images.githubusercontent.com/100543143/162658318-63030132-b108-41f9-9f95-e861a2e7d949.png)

The second thing we need to find out is if the employee can be a mentor and that is only required for how old the employee is.

![mentorship](https://user-images.githubusercontent.com/100543143/162658425-fd6cbf60-20de-4977-b594-54c2b7a538af.png)



## result ##

* Modeling the connections of points
* Collecting data into one file(retirement-info)
* Organizing the data 
* Collecting mentorship_eligibilty data from ranging


## Summary ##

Once we know what the files are holding in them we have to make connections and these connections will be showing us how to collect data in a way, so that the code allows it. To make things easy so we can see everything we just graph the subjects of the files.
![QuickDBD-export](https://user-images.githubusercontent.com/100543143/162656688-c3e65329-7517-42c7-ad1d-4de95630e81b.png)

After graphing we connect common data that the files have so that we can merge certain data into a new file
![retirement info3](https://user-images.githubusercontent.com/100543143/162657916-8da540e6-6fdf-48f2-80a5-5732a45cbd45.png)

For the mentorship eligiblty there is a requirement for the employees for them to be mentors, which is just they age. Depending on what age the employer wants you just limit the range of the table.
![mentorship](https://user-images.githubusercontent.com/100543143/162658236-2ca9cdfe-ea22-49ab-b69d-e97008318da2.png)
