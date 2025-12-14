# Interactive Network Analytics Dashboard

## Overview

This project is an interactive R Shiny web application for exploring group interaction patterns using Radio Frequency Identification (RFID) location-tracking data. The app allows users to investigate social network relationships through a point-and-click interface, without requiring advanced coding skills.

👉 Try the app: https://prashers.shinyapps.io/datascishinyapp/

Practice datasets are included in this repository.


## Problem Addressed

Analyzing interaction and movement data typically requires custom scripts and technical expertise, making it slow and inaccessible for many stakeholders. This tool removes that barrier by providing a self-service interface for exploring network relationships and interaction patterns directly from tracking data.


## What This App Does
- Automates data integration by merging RFID detections with individual identifiers
- Visualizes interaction networks with dynamic, interactive network graphs
- Allows parameter tuning via adjustable time windows to define interactions
- Computes network metrics (e.g., degree, interaction strength) in real time
- Supports data export with CSV downloads for reporting and downstream analysis


## Technical Implementation

The application is built using R Shiny and reactive programming to support real-time data exploration. It processes temporal tracking data, dynamically updates visualizations, and calculates network metrics on demand based on user-selected parameters.


## Impact

The app enables non-technical users to explore complex interaction data in minutes rather than hours of manual coding. It was originally developed for a data science module in undergraduate biology labs, requiring intuitive design for users with little to no programming experience, and is now **used by 950+ users annually**.


## Transferable Skills for Data & Product Analytics

This project demonstrates skills that are useful in data analyst, product analytics, and product data science roles, particularly those focused on self-service analytics and decision support.

- **Self-service analytics design**: Building tools that allow non-technical users to explore data and answer questions without writing code

- **Dashboard development**: Designing interactive, reactive dashboards that update in real time based on user inputs

- **Data integration and transformation**: Automatically merging, cleaning, and reshaping raw event data into analysis-ready formats

- **Exploratory analysis and visualization**: Enabling rapid exploration of patterns and relationships through dynamic visualizations

- **Metric computation**: Calculating and surfacing key quantitative metrics on demand (e.g., network statistics)

- **User-centered design**: Translating complex analytical workflows into intuitive interfaces for end users


## Skills Demonstrated
- R Programming
- Shiny Web Application Development
- Data Visualization
- Network Analysis
- Interactive Dashboard Design
- User-Centered Analytics


https://github.com/user-attachments/assets/1061ac27-e2df-475b-baf6-e00cf191425e



## Summary for educators:
This Shiny app was developed for an introductory biology lab course (BIOL1082L) at the University of Cincinnati to help students analyze and visualize penguin social networks using real RFID detection data. The app supports a newly introduced data science module that familiarizes students with R-based data analysis (app first developed in Fall 2022).

Students participate in interactive lab activities where they simulate penguin movements and generate RFID detection data. They then use the app to explore both their class-generated dataset and real penguin data from the Cincinnati Zoo. The app allows students to:

- Upload RFID detection data and merge it with penguin ID information.
- Adjust time thresholds for defining social associations.
- Generate interactive social network diagrams showing penguin interactions.
- Compute and download social network metrics (degree and strength) for each penguin.

By using this app, students gain hands-on experience with data visualization and network analysis in R without needing extensive coding knowledge.
