# Project 4: College Admissions Calculator
## Group Members: Amanda Hernandez, Ryan Essem, Nnamdi Ede, Jim Chen
## Overview

This is our fourth and final project for INST126 at the University of Maryland, College Park. For this project, we were given free reign to develop a program that tackles a real world problem. And as a group, we decided to create a college admissions calculator. Although this program cannot take into account the human biases that occur throughout the college admissions process, it can still provide students with a cohesive look at what factors are at stake during the admissions process. Overall, this program streamlines the ease of the college admissions process, helps relieve applicant stress, and allows for better planning and academic focus. 

Since the start of this project in late November, we have decided to deviate from our original idea and create a program that takes the user’s input (GPA, SAT score, and number of activities) and returns a message that explains their chances of being accepted, rejected, waitlisted, or deferred to the University of Maryland. The program will also read a text file that has the names, GPAs, SAT scores, and number of activities involved in about 100 randomized students and determine whether those students will be accepted, rejected, waitlisted, or deferred by comparing their information to ranges we have created for each admission decision. Then the program generates a scatter plot and histogram for further analysis. 

## How it works

When a user first runs the program, they will be asked to input their GPA, SAT score, and the number of activities they're involved in. Then, their GPA, SAT score, and the number of activities their involved in will be compared to several parameters that will ultimately determine the student's chances of being accepted, rejected, waitlisted, or deferred to the University of Maryland. The following are the parameters set in place: 

#### Accepted students must meet the following requirements: 
* GPA >= 3.0
* SAT >= 1250

#### Rejected students must meet the following requirements:
* GPA <= 2.7
* SAT <= 1100

#### Waitlisted students must meet the following requirements: 
* GPA in range (2.7, 3.0)
* SAT in range (1100, 1250)
* Activities == 4

#### Deferred students must meet the following requirements:
* GPA in range (2.7, 3.0)
* SAT in range (1100, 1250)
* Activities >= 5

The program will also read a text file that has the names, GPAs, SAT scores, and number of activities involved in of about 100 randomized students and determine the chances of a student to be accepted, rejected, waitlisted, or deferred to the University of Maryland by comparing their information to the paramaters defined above. The idea behind this is that it will help the user understand how they compare against other students. This gives it a bit of a more realistic element as well.

Then, the program will also return a scatter plot that displays dots to represent the students who were accepted, rejected, waitlisted, and deferred. This will also give the user an idea of the average GPAs and SATs that are accepted, rejected, waitlisted, and deferred. The x-axis of the scatterplot will be SAT scores while the y-axis will be GPAs. The plot will also be color coded so each admissions decision is represented by an easily identifiable color. And lastly, a histogram will also be generated that displays the number of activities waitlisted and deferred students are involved in. Because the number of activities a student is involved in determines whether or not they will be waitlisted or deferred, this also gives the user better insight on what they can do to better their chances of being admitted.

The graphics will look like the ones displayed below: 

![](images/scatter plot.png)
![](images/histogram.png)

## Update #1 (Nov. 25)

So far, we have collected the majority of the data that we need for this program. We are still looking for a national data set that contains high school student GPAs. We have also started experimenting with code and came up with code that can determine how many times a higher or equal GPA/SAT score appears in a data set compared to the GPA and SAT score entered by a user.

## Update #2 (Dec. 2)

After our last update, we decided to change how the code/overall project would be structured as well as what information it would return to the user. Initially, we wanted to create a program that would calculate a user’s chances of getting into five different schools based on only their GPA and SAT score. The program would then return an individualized rank (1-5) of the schools for the user. The ranking would have been based on how closely the user's GPA and SAT score matched the average GPAs and SAT scores of the five different universities. Instead of going forward with this plan, we wanted to create a more realistic and useful program for students which is explained in full above. We also updated our flowcharts to reflect the changes and designated sections of the code to each group member. 
