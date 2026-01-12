# Probability for Machine Learning

## Why this matters
Machine learning is built on uncertainty.

Data is noisy.  
Labels are imperfect.  
Models never know the truth — they only estimate probabilities.

This file captures how I am learning probability as the foundation of statistical and machine learning models.

---

## What probability really means
Probability measures how likely something is to happen, on a scale from 0 to 1.

In AI, probability is used to answer questions like:
- How likely is this email to be spam?
- What is the chance this patient has a disease?
- How confident is the model in this prediction?

---

## Core Objects

### Sample Space
The set of all possible outcomes.

In ML:
- All possible labels a model could predict
- All possible values a variable could take

---

### Events
An event is a specific outcome or group of outcomes we care about.

Example:
- “This image is a cat”
- “This transaction is fraudulent”

---

## Basic Probability Rule
P(Event) = (Number of times it happens) / (Total number of observations)

In data-driven AI, this usually comes from observed data, not theoretical counting.

---

## Conditional Probability
This is one of the most important ideas in AI.


It means:
> How likely is A when I already know B happened?

Example:
- Probability a patient has a disease **given** a positive test result  
- Probability an email is spam **given** certain words appear

Bayesian models and many classifiers are built on this idea.

---

## Key Rules

| Rule | Why it matters |
|------|----------------|
| Addition rule | Used when combining possible outcomes |
| Multiplication rule | Used when events depend on each other |
| Complement rule | Helps measure uncertainty and error |

---

## How this shows up in machine learning
- Logistic regression outputs probabilities
- Naive Bayes models use conditional probabilities
- Neural networks estimate probability distributions
- Model confidence and uncertainty come from probability theory

---

## Learning Sources
- Engineering Mathematics – Dexter J. Booth  
- Online ML-focused probability tutorials (to be expanded)
