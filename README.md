"""
# Spaceship Titanic Prediction

This repository contains a machine learning project to predict whether a passenger was transported to an alternate dimension during the Spaceship Titanic's collision with the spacetime anomaly..

## Project Structure
```
.
├── README.md
└── task_1
    ├── task_1.ipynb       # jupyter notebook with model + EDA
    └── task_1.md           # Documentation & explanation
```

## Dataset Info
The dataset consists of passenger records. Each record has features such as:
- HomePlanet
- CryoSleep
- Destination
- Cabin (split into Deck, Num, Side)
- Spending (RoomService, FoodCourt, Spa, etc.)
- Age, VIP status, etc.

## Goal
Predict whether a passenger was **Transported** (target: True/False).

## Approach
- Data preprocessing (filling missing values, cabin splitting)
- EDA with Seaborn plots (making the data visualization easier)
- One-hot encoding
- Train/validation split
- Model training with RandomForestClassifier (algorithm used for classification tasks like predicting True/False, or Pass/Fail)
- Accuracy check
- Create final submission.csv

---
"""
