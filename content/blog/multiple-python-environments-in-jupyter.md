---
title: "Using Multiple Python Environments in Jupyter"
description: "A refreshed legacy guide to how Jupyter kernels make it possible to work with more than one Python environment."
date: 2019-06-03
draft: false
tags: ["Jupyter", "Python", "Environments", "Notebooks", "Kernels"]
---

> Editor's note: this article is based on an older post from my WordPress archive and has been rewritten for my current portfolio.

One of the most useful parts of the Jupyter ecosystem is that notebooks are separated from kernels.

That separation matters because it means a notebook interface can work with different language runtimes and different Python environments, instead of being tied to only one installation. 🧪

## Why this problem shows up

Sooner or later, many people end up needing:

- one environment for an older project
- another environment for newer packages
- a clean environment for experiments
- a separate environment for teaching or demos

If everything is installed into one place, dependency conflicts show up fast.

## The key idea: kernels

According to the Jupyter documentation, kernels are language-specific processes that run independently from the notebook interface.

That means:

- Jupyter is the interface
- the kernel is the runtime that executes the code

Once you understand that distinction, the idea of multiple Python environments becomes much easier.

## Why multiple environments are useful

They help you:

- isolate package versions
- avoid breaking older projects
- test work in cleaner setups
- switch between different project stacks safely

This is one of the small habits that saves a lot of pain later. ✅

## A good mental model

Think of Jupyter as the workspace and kernels as the engines you can attach to it.

The notebook does not need to care whether the runtime behind it is:

- one Python version
- another Python version
- or even another language entirely

That flexibility is part of what made Jupyter so durable.

## Why this still matters

Even though environment management has improved over time, the underlying workflow problem is still the same in 2026:

different projects often need different dependencies.

If you work with notebooks seriously, understanding kernels and environments is still a very practical skill.

## Final thought

Jupyter becomes much less confusing once you understand that the notebook and the runtime are not the same thing.

That single idea explains a lot of how the ecosystem works. 🔧
