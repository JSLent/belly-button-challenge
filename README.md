# belly-button-challenge
Repo for Module 14 Challenge

# Bacteria Biodiversity Dashboard

## Overview

This Challenge had us create a web-based, interactive dashboard to visualize the bacterial species (also known as Operational Taxonomic Units, or OTUs) that colonize human navels. The dataset used in this project is from a research study called "The Belly Button Biodiversity Dataset" (https://robdunnlab.com/projects/belly-button-biodiversity/).  

## Features

The dashboard provides the following visualizations:

1. **Bar Chart**: Displays the top 10 OTUs found in a selected individual's belly button. The OTU IDs are used as labels, the sample values as values, and the OTU labels as hovertext.

2. **Bubble Chart**: Displays each sample with OTU IDs for the x values, sample values for the y values and marker size, OTU IDs for the marker colors, and OTU labels for the text values.

3. **Metadata Panel**: Displays an individual's demographic information. Each key-value pair from the metadata JSON object is displayed in this panel.

The dashboard also includes a dropdown menu for selecting different individuals' samples. When a new sample is selected, all the plots and the metadata panel are updated.

## Technologies Used

- JavaScript
- D3.js
- Plotly.js

## How to Run

Go to https://jslent.github.io/belly-button-challenge/ or open the `index.html` file in a web browser to view the dashboard.


