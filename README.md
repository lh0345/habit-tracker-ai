# Habit Tracker AI

A habit tracking application built with Next.js and TypeScript that uses machine-learning models to estimate habit completion.

The main technical part of this project was implementing the machine-learning logic directly in TypeScript rather than depending on an external ML library.

## What I Implemented

* Habit creation and completion tracking
* Habit statistics and historical data
* Feature extraction from habit data
* A logistic regression classifier written from scratch
* A decision tree classifier written from scratch
* Model training and prediction logic
* Model evaluation code
* A prediction engine that connects the models to the application
* Sample-data generation for testing
* Local application storage
* Input validation
* Automated tests with Jest

## Machine Learning Work

### Logistic Regression

I implemented:

* Model weights and bias
* The sigmoid function
* Probability prediction
* Iterative training
* Error calculation
* Gradient-based weight and bias updates

### Decision Tree

I implemented:

* Tree nodes
* Gini impurity calculation
* Feature and threshold testing
* Weighted split comparison
* Recursive tree construction
* Maximum-depth and minimum-sample stopping rules
* Tree traversal for predictions

## What I Learned

This project helped me understand what common machine-learning algorithms do internally.

Writing logistic regression myself taught me how a set of input features becomes a weighted value, how the sigmoid function converts that value into a probability, and how training changes weights based on prediction errors.

Writing the decision tree taught me how a model tests possible splits, measures impurity, selects a useful threshold, and recursively creates branches.

I also learned that using machine learning inside an application requires more than the model itself. Raw application data needs to become numerical features, training data needs labels, predictions need to connect back to the UI, and model behavior needs testing and evaluation.

## What This Project Demonstrates

* TypeScript
* Next.js and React
* Machine-learning fundamentals
* Logistic regression
* Gradient-based training
* Decision trees
* Gini impurity
* Feature engineering
* Model evaluation
* Application testing

## Tech Used

* Next.js
* React
* TypeScript
* Jest
* Zod
* Recharts
* Browser storage

## Running the Project

```bash
npm install
npm run dev
```

Run the tests with:

```bash
npm test
```
