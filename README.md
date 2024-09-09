# Dots Dataset -Project Overview

## Introduction
This project uses the dots dataset from the Seaborn library to explore patterns in firing rates over time.
The dots dataset includes simulated data on the firing rate of neurons, measured at different times, under various experimental conditions.
This project focuses on understanding how different levels of coherence and choice affect the firing rate over time.

## Dataset Information

## Dataset Name:  dots

## Source: The dataset is included with the Seaborn library.

## Description: This dataset contains simulated data that represents the firing rates of neurons under various experimental conditions. The key variables are:
coherence: The level of coherence in the visual stimulus (a factor influencing neuron firing).
choice: A binary variable indicating whether the correct or incorrect choice was made.
time: The time at which the firing rate was measured.
firing_rate: The firing rate of the neuron at the given time.

## Project Steps

1. Data Loading
We begin by importing the necessary libraries (Seaborn and Matplotlib) and loading the dataset using Seaborn's load_dataset() function.
We inspect the dataset by displaying the first few rows and checking its structure.

3. Data Exploration
We explore the dataset to understand its structure. This includes:

Checking the data types of the columns.
Describing the summary statistics for numerical columns.
Identifying any missing values in the dataset.

3. Data Cleaning
If necessary, missing values are handled by either filling them or removing rows with missing data.

4. Data Visualization
A series of visualizations are created to gain insights into the relationships within the data:

Scatter Plot: We visualize the relationship between time and firing_rate, colored by coherence and styled by choice.
Line Plot: Trends in firing_rate over time are examined for different levels of coherence and choice.
Distribution Plot: The distribution of firing_rate for different coherence levels is visualized.
Pairplot: Multiple relationships between variables are explored to understand how different variables interact with one another.



5. Analysis & Insights
From the visualizations, we analyze:

How the firing rate changes over time based on the level of coherence and choice.
The distribution of firing rates and the effect of coherence on the firing rates.
Key trends in how different experimental conditions affect neuron behavior.
6. Conclusions
The key conclusions from this project are:

The firing rate tends to increase with higher levels of coherence.
There is a noticeable trend in firing rate over time, with coherence and choice influencing it.
The firing rate distribution shows that certain levels of coherence lead to higher firing rates.



