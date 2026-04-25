---
title: "Bias and Variance in Plain English"
description: "A refreshed legacy explainer on underfitting, overfitting, and why machine learning models fail to generalize."
date: 2019-06-18
draft: false
tags: ["Machine Learning", "Bias", "Variance", "Model Evaluation", "AI"]
cover:
  image: "/blog/bias-and-variance-in-plain-english/cover.svg"
  alt: "Bias and variance cover illustration"
---

> Editor's note: this article is based on an older post from my WordPress archive and has been rewritten for my current portfolio.

Bias and variance are two of the most useful ideas for understanding why a machine learning model performs poorly.

If a model does not generalize well, the problem is often not mysterious. In many cases, the model is either:

- too simple to learn the real pattern
- too sensitive to the training data

Those two failure modes are what people usually mean when they talk about **bias** and **variance**. 🤖

## A simple way to think about prediction error

At a high level, prediction error is the gap between what the model predicts and what actually happens.

When we evaluate a model, we want to know:

- does it miss the real pattern entirely?
- or does it fit the training data too closely and fail on new data?

Bias and variance help answer those questions.

## What bias means

Bias is what happens when a model is too rigid or too simple to capture the underlying pattern in the data.

If the model makes consistently wrong assumptions, it will miss important structure and perform poorly even on the training data.

This usually leads to **underfitting**.

### Signs of high bias

- training performance is weak
- test performance is also weak
- predictions are systematically off

### Intuition

Imagine trying to describe a curved pattern with a straight line. Even if the data is clean, the model is too limited to learn what is really happening.

## What variance means

Variance is what happens when a model becomes too sensitive to the exact training examples it has seen.

Instead of learning the real signal, it starts learning noise, quirks, and accidental details in the training data.

This usually leads to **overfitting**.

### Signs of high variance

- training performance is very strong
- test or validation performance drops
- predictions change too much when the input data shifts slightly

### Intuition

Imagine memorizing practice questions instead of understanding the subject. You may score well on the familiar examples, but struggle when the questions change.

## The tradeoff

Most model-building work is really about balancing these two problems:

- too much bias and the model is too crude
- too much variance and the model is too fragile

![Animated sketch of the bias-variance tradeoff across increasing model complexity](/blog/bias-and-variance-in-plain-english/bias-variance-tradeoff.gif)

The goal is not zero bias or zero variance. The goal is to find a model that captures useful structure without becoming overly dependent on the training set.

## How people usually reduce bias

To reduce bias, teams often:

- use a more expressive model
- add better features
- improve the representation of the data
- train longer when appropriate

## How people usually reduce variance

To reduce variance, teams often:

- simplify the model
- use regularization
- collect more data
- improve train-validation-test splits
- reduce noisy or irrelevant features

## Why this still matters

Even with modern models, this concept remains foundational. Whether you are working with regression, tree models, deep learning, or recommender systems, the question is still the same:

Is the model failing because it cannot learn enough, or because it learned too much of the wrong thing?

That is why bias and variance remain such useful mental models in machine learning. 🧠

## Final thought

If you remember one thing, remember this:

- **high bias** usually means underfitting
- **high variance** usually means overfitting

Once you understand that distinction, debugging model behavior becomes much easier.
