<!-- This markdown describes the final project by Paul Kallio for the Building of AI course,
that is created by Reaktor Innovations and University of Helsinki. -->

# AI Team Builder

## Summary

The aim of this AI project is to create application, that is capable of select the team, that is good enough to execute the given task.
<br /><br />
![Team](https://github.com/paulmkallio/football_team_builder/blob/main/our_team.jpg)

## Background

Most companies that work in teams have various resources containing key persons, inexperienced workers and bag of professionals with different technical knowledge. Also the tasks are different and competence needed to manage them variates. For example consultant company has few lead designers, some administrators and many programmers in UI and server side. Key players and other sparse resources are used only when needed and workload got to spread evenly to the others. This same applies to any business area using teams like construction companies.

## How is it used?

Team management can use this as an aid, when they plan the next project. This solution is needed especially, when the next task is not that critical based on the size of the customer or time span of the project. Approximation of the quality of the team member can be used as a weight of position needed. Vulnerabilities and strengths of the team in some areas can be used as an bias in calculation.

## Data sources and AI methods

Data used is taken from our own data lake, adding common statistics when available.
Model is built using Neural Networks using Backpropagation. System uses ReLU as an activation function
to keep execution time feasible. Hidden layers are limited to three to avoid Overfitting problem.
Weights and biases are created by the management.
In the long run these too will be extracted from our own data source.

## Challenges

Quality of the staff is variating, so output of the team has always some limitations.

## What next?

Next steps are to collect and normalize the data, decide weights and biases with our managers and HR,
design outlook of our reporting, and then write the actual code with Python using Numpy, Matplotlib and SKlearn.
System is built on Apache Spark.

## Acknowledgments

Sources of inspiration:
https://buildingai.elementsofai.com/ by Reaktor Innovations and University of Helsinki.

<br> [Team](https://www.birosgb.com/wp-content/uploads/2018/08/our_team.jpg#filelinks) from https://www.birosgb.com.
