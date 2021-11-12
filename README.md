# Playstore Analysis

One of the most important goals of online stores is to promote products due to the recommendation system. Therefore, the store aims to know the highest rated applications because this reflects the performance and quality of the application. By knowing the interests of customers in terms of evaluation or even interest in the application category, the store will be able to promote the applications that are most interested by customers.



## Contents

-[Problem Statement](#Problem_Statement)

-[Data Description](#Data_Description) 

-[Tools](#Tools)

-[Installation](#Installation)

-[Questions](#Questions) 

-[Dataset Resource](#Dataset_Resource)

-[Author](#Author)


![Logo](https://arabhardware.net/wp-content/uploads/2020/02/new-google-play-store-mobile-1280x720.jpg)


## Problem_Statement

Company (A) wants to create a new application in Google Play, so it wants to know the most important reasons for the success of applications in the store.
### Data_Description

Dataset: Google Play Store data (“googleplaystore.csv”). 

It has 10841 rows , 10 columns.

| Field Name        | Description| 
| ------------- |:-------------:| 
| App      | Application name | 
| Category      | Category to which the app belongs      |  
| Rating | Overall user rating of the app      |
| Reviews    | Number of user reviews for the app |
| Size       | Size of the app |
| Installs   | Number of user installs for the app |
| Type       | Paid or Free |
| Price      | The price of the app Content Rating: Age group the app is targeted at - Everyone can access / 10+ / 17+ / 18+ |

## Tools
Jupyter Notebook

Language: Python

Libraries: numpy, pandas, seaborn

## Installation

Run pip install command to install related packages.

```bash
!pip install numpy
!pip install pandas
!pip install seaborn
```
    
## Questions
1. Does rating have a role in increasing the number of downloads?

2. Does age classification have a role in increasing the number of downloads?

3. Is there a relationship between the category and the number of downloads?

4. Does the price affect the number of downloads and evaluations?
## Dataset_Resource

https://www.kaggle.com/madhav000/playstore-analysis/version/1
## Author

[@YasserMohammedK](https://github.com/YasserMohammedK)

