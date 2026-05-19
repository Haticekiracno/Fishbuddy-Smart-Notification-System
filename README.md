# 🎣 FishBuddy – Smart Notification System

Bachelor project developed in collaboration with FishBuddy and the University of Agder.

A data-driven notification system designed to improve user engagement and support premium features through personalized fishing recommendations.

> Source code is private due to company confidentiality agreements.



## Overview

The project combines:

- Historical catch data
- Weather forecasts from MET API
- Statistical modeling
- Personalized recommendations
- Smart notification logic

The goal was to help recreational fishers make better decisions by identifying favorable fishing conditions.



## Problem

FishBuddy uses a freemium model, where many users remain free users and rarely engage with the application.

We wanted to answer:

"How can historical catch data and weather forecasts be combined to create useful recommendations and increase engagement?"



## My Contribution

My main responsibilities included:

- UX design and user-centered thinking
- Wireframes and prototypes
- User flow planning
- Testing and usability evaluation
- Cross-team collaboration

I also contributed across multiple areas throughout the project.



## Tech Stack

Python  
Pandas  
Streamlit  
REST API  
MET Weather API  
GitHub  
Jira  
Scrum



## Data & Analysis

Dataset:

- 19,842 catch records
- 2,217 unique users
- Filtered to 7,654 validated observations
- 38 fish species analyzed

The model combines:

### Poisson Regression
Used to determine how much environmental factors influence catch outcomes.

Factors:

- temperature
- pressure
- wind
- cloud coverage
- precipitation
- season

### Gaussian Similarity Scoring

Used to compare predicted weather against historical fish profiles.


## Testing

The project included:

- Unit testing
- Integration testing
- Edge-case testing
- Performance testing

42 tests completed successfully.



## Development Process

The project followed Scrum methodology:

- Sprint Planning
- Daily Scrum
- Sprint Review
- Jira project management

Developed across four iterations.



## Results

The system successfully differentiated between seasonal and weather conditions and generated meaningful recommendation scores.

Spring conditions produced significantly stronger fishing predictions than winter conditions.


## Project Context

Developed as part of a Bachelor thesis at University of Agder in collaboration with FishBuddy.
