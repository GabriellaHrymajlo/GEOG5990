# Public Transport Accessibility & Employment Rates in Greater Manchester  

# Project Overview  
This project investigates whether areas with better public transport accessibility in Greater Manchester have higher employment rates. Using 2011 Census data, we analyse the relationship between commuting distances, travel modes, and employment outcomes at the MSOA (Middle Super Output Area) level. Additionally, bus stop locations provide insights into transport accessibility.  

The goal is to determine whether higher public transport reliance correlates with improved employment levels, supporting evidence-based decision-making in transport planning and employment policy.  

# Data Included in This Repository  
This GitHub repository contains:  
- 'england_msoa_2011.shp': Geospatial shapefile defining MSOA boundaries within Manchester.
- 'TfGMStoppingPoints.csv': Spatial dataset of bus stop coordinates for accessibility analysis.
- 'distancework.csv': Data detailing the distance of people commuting to work per MSOA in Manchester.
- 'transport.csv': Data detailing the mode of transport people use to commute to work per MSOA in Manchester.
- 'employmentdata.csv': Raw numbers of those unemployed per MSOA in Manchester

# Aim of the Code  
This repository follows a full data science workflow, including:  
- Data Cleaning & Preprocessing and Exploratory Data Analysis: Looking for outliers and standardising coordinate systems. Generating summary statistics and histograms for key variables.
- Statistical Modelling: Creating a statistical model between the variables chosen. 
- Non-Spatial Visualisations: Creating a bar chart to identify trends.
- Spatial Visulisation: Spatially joining all CSV data with MSOA boundaries to be able to create a geospatial visulisation showing the geography of different variables.

# Data Attributions
Office for National Statistics (ONS) (2025) Middle Super Output Area (MSOA) Boundaries. UK Data Service Census Support. Available at: https://borders.ukdataservice.ac.uk/bds.html (Accessed: 13 May 2025).
Transport for Greater Manchester (2024) Bus Stopping Points Dataset. Contains OS data © Crown copyright and database right 2024. Available at: https://www.data.gov.uk/dataset/05252e3a-acdf-428b-9314-80ac7b17ab76/bus-stopping-points (Accessed: [13/05/2025])


