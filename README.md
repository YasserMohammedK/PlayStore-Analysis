# Playstore Analysis

At the beginning of creating any application, companies need to know the influencing factors required for the success of their application. So this dataset will help us to know some of these factors.



## Contents

-[Problem Statement](#Problem_Statement)

-[Data Description](#Data_Description) 

-[Tools](#Tools)

-[Installation](#Installation)

-[Questions](#Questions)

-[MVP Goal](#MVP)

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

Libraries: numpy, pandas, seaborn, plotly, matplotlib

## Installation

Run pip install command to install related packages.

```bash
!pip install numpy
!pip install pandas
!pip install seaborn
!pip install plotly
!pip install matplotlib
```
    
## Questions
1. Does Rating have a role in increasing the number of downloads?

2. Does Targets have a role in increasing the number of downloads?

3. Is there a relationship between the Category and the number of downloads?

4. Does the price affect the number of downloads and Rating?

5. What is the category with the highest number of installs?

6. Is the category with the highest number of installs also has the highest average in installs?  
## MVP

To find some factors that increase the probability of applications success 
## Dataset_Resource

https://www.kaggle.com/madhav000/playstore-analysis/version/1
## Author

[@YasserMohammedK](https://github.com/YasserMohammedK)

