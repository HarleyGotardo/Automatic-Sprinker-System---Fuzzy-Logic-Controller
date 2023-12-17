# Fuzzy Logic Controller for Sprinkler System

## Overview
This Python script implements a Fuzzy Logic Controller (FLC) to control the operation of a garden sprinkler system based on soil moisture levels and weather conditions. The FLC takes user inputs for soil moisture and weather conditions, applies fuzzy logic rules, and generates an output representing the recommended sprinkler operation duration.

## Universe Variables
- **Soil Moisture Level (Percentage):**
  - Dry
  - Moist
  - Wet

- **Weather Conditions (Chance of Rainfall):**
  - Sunny
  - Cloudy
  - Rainy

- **Sprinkler Operation Duration (Minutes):**
  - Short
  - Medium
  - Long

## Membership Functions
The script defines membership functions for each universe variable to capture the linguistic terms associated with them.

## Rule Base
The fuzzy logic rules determine the sprinkler operation duration based on the combination of soil moisture and weather conditions.

## Fuzzy Inference
The user inputs are fuzzified using the defined membership functions, and fuzzy rules are applied to determine the sprinkler operation duration.

## Centroid Calculation
The centroid (center of gravity) of the aggregated membership function is calculated to obtain the final output.

## Output Visualization
The script includes plots to visualize the membership functions and the resulting fuzzy output for sprinkler operation duration.
