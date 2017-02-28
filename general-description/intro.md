# Motivation
Every data science specialist faced with the necessity of exploratory data analysis (EDA). This contains:

1. Load data from different sources and formats;
2. Data investigation and exploration;
3. Data Transformation;
4. Visualization.

For all these operations spend much time and often data scientists miss some less or more important details. 
And with this in mind, we decide to create a tool to relief the process.

# Overview

### Moto - **Just plug and play with your data!**

DataStack is simple to setup and run.
It is not the web(cloud) based application, it just has the web interface to work with data.

The current software provides next functionality for data sciences:

1. Load data from a file that contains data in different formats (CSV, TSV, excel, hdf, etc.);
2. Keeps data locally on your hard drive cataloged;
3. Display file data via web interface;
4. Provide samples overview:
 * A description of the entities;
 * Data dependency;
 * Distribution;
 * Сorrelation;
5. Data visualization:
 * Lines plots;
 * Scatter plot;
 * Bar chart;
 * Maps.

# Communications

* [Slack](https://data-stack.slack.com)

# Releases plan

## v0.1 (work in progress)

* Load data from a file (CSV, TSV, etc.)
* Keep data locally on your hard drive
* Keep sample in memory to speed up calculations
* Keep context in memory: head, data annotations, mean, median
* Display file data via web interface

## v0.2

* Load data from DB, API, Binary data
* Data transformation

# Technology stack

TBD

## Backend

* asyncio
* pandas

In future:

* dash
* swagger

## Frontend

* ng-admin2 (or some analog)

# UX design

TBD

# Task management

Trello

# Architecture overview

TBD

# Release management

TBD
