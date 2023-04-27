## Misinformaiton Detection in Health Posts

### Introduction

This is a machine learning model trained with [health posts related to COVID-19 on Weibo](https://github.com/cyang03/CHECKED).<br>
The purpose of it is to detect misinformation on social media and the features extracted are linguistic features of several linguistic levels.

| Linguistic Level | Feature |
| :--------------- | :------ |
| punctuation | exclamation_marks<br>question_marks |
| semantic | entropy |
| semantic-syntactic | dependency_distance |
| syntactic | average_length<br>cohesion |
| pragmatic | imperative<br>interrogative |

### Additional Information
The whole process of this project was done with R language except for the calculation of dependency distance. The dependency distance was calculated in python with the assistance of <code>stanza</code>.
