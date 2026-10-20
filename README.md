# Data Science Project Portfolio

This repository contains a collection of my data science and visualization projects, demonstrating my skills in data wrangling, statistical analysis, and spatial data visualization using Python.

## Project 1: Casino F&B vs. Local Restaurant Revenue (Assignment 02)

### The problem or research question
Does the post-pandemic surge in complimentary F&B expenditure by Macao's gaming operators correlate with the ongoing financial struggles of local restaurants?

### Dataset source and usage permissions
Statistics and Census Service (DSEC), Macao SAR. Publicly available official statistics.

### Methods and tools used
Python (Pandas, Matplotlib) for data cleaning, aggregation, and composite dual-axis visualization.

### Key findings and one limitation
**Findings:** The "scissors gap" reveals that casino complimentary expenditure skyrocketed post-pandemic, while local restaurant profit margins remained razor-thin, showing preliminary evidence of a partial crowding-out effect.
**Limitation:** This is an observational correlation, not proven causation. Confounding factors like rent and labor costs were not isolated.

---

## Project 2: US States Choropleth Map (Suggested Exercise 8.02)

### The problem or research question
How to effectively visualize statistical variables across different geographical areas using GeoJSON data?

### Dataset source and usage permissions
Provided GeoJSON dataset (`us_states.json`) containing US state boundaries and Census Area data.

### Methods and tools used
Python (JSON, Geoplotlib, Matplotlib, GeoPandas) for parsing geospatial data and rendering a choropleth map.

### Key findings and one limitation
**Findings:** Successfully generated a visual representation of the USA, demonstrating the ability to handle and plot complex geospatial geometries.
**Limitation:** The base map rendering in `geoplotlib` requires internet connectivity and specific older library versions, requiring alternative rendering workarounds.

---

## Instructions for running the analysis
1. Ensure all dependencies listed in `requirements.txt` are installed.
2. Open the respective `.ipynb` files (Assignment 02 or Activity 8.02) in Jupyter Notebook.
3. Run the cells sequentially from top to bottom to reproduce the visualizations.
