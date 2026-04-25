---
title: "Python Libraries for Data Science"
description: "A refreshed legacy guide to useful Python libraries for data analysis, machine learning, visualization, and data engineering workflows."
date: 2017-03-14
draft: false
tags: ["Python", "Data Science", "Machine Learning", "Visualization", "Libraries"]
---

> Editor's note: this article is based on an older post from my WordPress archive and has been rewritten for my current portfolio.

The Python ecosystem is one of the main reasons data work became so accessible. You can move from cleaning messy tables to training models, building dashboards, or scaling workflows without switching languages every few hours.

That does not mean every library matters equally. The useful question in 2026 is not “what are all the libraries?” It is “which libraries are worth learning first, and what are they actually good for?” 🐍

## 1. Data manipulation and analysis

### `pandas`

If you work with tabular data, `pandas` is still one of the first libraries to learn.

It is useful for:

- reading and writing files
- cleaning data
- joining datasets
- grouping and aggregating records
- reshaping tables
- basic time-series work

For many analytics tasks, `pandas` is where the real project begins.

### `NumPy`

`NumPy` provides the array operations that power much of the scientific Python stack. Even if you do not use it directly every day, you will benefit from understanding vectors, matrices, broadcasting, and numerical operations.

## 2. Machine learning

### `scikit-learn`

`scikit-learn` remains one of the best libraries for classical machine learning. It is practical, well-documented, and ideal for:

- classification
- regression
- clustering
- preprocessing
- model selection
- evaluation workflows

If someone wants to learn modeling fundamentals, this is still one of the best places to start. 🤖

### `gensim`

`gensim` is useful for topic modeling, document similarity, and some NLP workflows involving semantic structure in text collections.

## 3. Natural language processing

### `NLTK`

`NLTK` is still a good teaching library for learning the basics of tokenization, corpora, linguistic structure, and introductory NLP workflows.

### Other NLP libraries

In practice, modern NLP work often also includes libraries such as `spaCy`, transformer tooling, and production-oriented text pipelines. But `NLTK` still has value when you want to understand the foundations.

## 4. Visualization

### `Matplotlib`

`Matplotlib` remains foundational. It may not be the prettiest tool by default, but it gives you control and sits under many other Python visualization workflows.

### `seaborn`

`seaborn` is useful when you want statistical visualizations with less boilerplate and better defaults.

### `Bokeh`

`Bokeh` is useful for interactive browser-based plots and data apps, especially when you want something richer than static figures.

## 5. Scientific and numerical computing

### `SciPy`

`SciPy` builds on NumPy and helps with scientific computing tasks such as optimization, interpolation, linear algebra, and signal processing.

## 6. Data engineering and larger-scale workflows

Some of the older tools from my original post still make sense conceptually, but the ecosystem has evolved.

Useful categories today include:

- workflow orchestration
- distributed computation
- storage and file formats
- database connectivity

### `Dask`

`Dask` is a practical library for parallel and larger-than-memory data workflows in Python. It is helpful when pandas alone starts to feel constrained.

### `PyMongo`

If you work with MongoDB from Python, `PyMongo` remains the standard connector.

### `h5py`

Useful when dealing with structured scientific datasets stored in HDF5 format.

### Workflow tooling

My original post mentioned tools like `Luigi`, which was a reasonable choice in that era. Today, teams often think in terms of broader orchestration ecosystems, but the core need is the same: define dependencies, run tasks reliably, and manage data workflows at scale. ⚙️

## How to think about this list in 2026

Do not try to learn every library at once. A better path is:

1. learn `pandas` and `NumPy`
2. add `matplotlib` or `seaborn`
3. learn `scikit-learn`
4. branch into NLP, visualization, or data engineering depending on your work

The right stack depends on what you actually want to build.

## Final thought

Python is powerful because the ecosystem lets you move from exploration to production with surprisingly little friction. The key is not collecting tools. It is choosing the smallest useful set that helps you solve real problems. 📈
