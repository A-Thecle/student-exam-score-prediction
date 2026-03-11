# Student Exam Score Prediction using Deep Learning

## Project Overview

This project aims to predict **students' exam scores** based on their productivity and lifestyle habits.
A **Neural Network implemented with NumPy** is used to learn patterns from the dataset and estimate the final exam score.

The goal is to understand how factors such as study time, sleep duration, social media usage, and mental health influence academic performance.

---

## Dataset

The dataset used in this project contains several variables describing students' daily habits and productivity levels.

### Features

* Age
* Gender
* Academic level
* Study hours
* Self-study hours
* Online classes hours
* Social media usage
* Gaming hours
* Sleep hours
* Screen time
* Exercise minutes
* Caffeine intake
* Part-time job
* Upcoming deadlines
* Internet quality
* Mental health score
* Focus index
* Burnout level
* Productivity score

### Target Variable

* **Exam Score** → the final grade obtained by the student.

---


## Methodology

### 1. Data Preprocessing

* Handling categorical variables
* Feature normalization
* Splitting dataset into **training** and **testing** sets

### 2. Model

A **fully connected neural network** was implemented using NumPy.

Architecture example:

```
Input layer → Hidden layer (8 neurons) → Hidden layer (4 neurons) → Output layer
```

Activation functions and forward/backpropagation were implemented manually.

### 3. Training

The model was trained using:

* Gradient descent
* Backpropagation
* Mean Squared Error (MSE) as the loss function

### 4. Evaluation Metrics

To evaluate the regression model, the following metrics were used:

* **Loss (MSE)**
* **Mean Squared Error**
* **R² Score**

These metrics help determine how well the model predicts exam scores.

---

## Results

During training:

* **Loss and MSE decrease over iterations**
* **R² score increases**, showing that the model learns meaningful patterns.

Visualization includes:

* Training vs Test Loss
* Training vs Test MSE
* Training vs Test R² Score

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---




