# Software Reliability Model - reliability-model

This Software Reliability Model (SRM) provides a flexible and explainable model of software reliability in terms of inputs, outputs, drivers, activities, and forces. It is designed to help explore and explain software reliability to people of various roles who are involved in building and running software systems. The SRM is also designed to make it easy to generate and update hierarchical metrics for product health scores across multiple teams.

## Audience

The SRM is aimed at these kinds of people:

* Product Owner / Product Manager
* [SRE](https://sre.google/) Manager / [SRE](https://sre.google/) Lead
* Software Architect / Systems Architect / Test Architect
* Software Developer
* Software Tester

The SRM helps these people to explore and discuss different aspects of software reliability to help make targeted improvements.

## What's in the SRM?

The SRM is composed of 2 main parts:

1. definitions of reliability factors in CSV format suitable for import to [Kumu](https://kumu.io/) 📄
2. graphs in [Kumu](https://kumu.io/) generated by importing the CSV definitions 📊

The CSV files are imported into Kumu to generate explorable graphs.

# Explore the latest version of the model on Kumu

Visit the latest version of the [reliability-model](https://kumu.io/reliability-model/latest) on Kumu.

TODO: add image

# Types of factors in the model

There are several types of factors in the SRM - each factor type is shown differently in the Kumu graph:

* activity - something that happens
* input - something enters the system
* metric - something measurable
* output - something that exits the system
* pattern - a design or template that can be applied to different situations
* practice - something we do as professionals
* quality attribute - an aspect or dimension of the software
* technique - a way of doing something, usually involving tools

## Tags help explore the model

Tags are used to explore different dimensions of the model:

* 4 Key Metrics - from Accelerate
* external - something outside from the system
* internal - something inside the system
* tool - technology that provides a capability


# Possible improvements

* Use CI to test Pull Requests against Kumu import:
  - Duplicate nodes?
  - Dangling connectors?
