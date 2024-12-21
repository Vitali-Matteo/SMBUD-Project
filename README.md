# Systems and Methods For Big and Unstructured Data - PoliMI Project

This repository contains the project work for the Systems and Methods For Big and Unstructured Data course at Politecnico di Milano.

## Project Overview

The project consists of three main components:
1. Data wrangling and loading
2. MongoDB queries with reesults visualization and interpretation
3. Sentiment analysis on reviews

## Repository Structure

- **Dump/**

  Contains links to the dataset and CSV files with sentiment analysis results

- **Images/**

  High-resolution images used in the project report

- **Report/**

  LaTeX source files for the project report

- **Preprocessing.ipynb**

  Jupyter notebook containing data wrangling and loading

- **Queries.ipynb**

  Jupyter notebook with MongoDB queries covering the following analyses:
    - Query 1: How many businesses and reviews for each category?
    - Query 2: For each category, find the most polarizing business
    - Query 3: Find in which city a chain of businesses performs the best
    - Query 4: Establish whether local competitions influences average and variance review stars
    - Query 5: Are day and night reviews biased?
    - Query 6: Do friends have similar ratings?
    - Query 7: Yearly growth rate of businesses
    - Query 8: Cities with lowest sentiment for each category
    - Query 9: Number of businesses for each bucket of possible reviews ratings
    - Query 10: Investigate the relation between sentiment and stars of reviews
    - Query 11: Search for reviews outlayers

- **Sentiment_analysis.ipynb**

  Jupyter notebook containing sentiment analysis implementation and results

- **SMBUD Project - Matteo Vitali.pdf**

  Final project report

## Requirements

- MongoDB
- Python 3.x
- Required Python packages:
  - pandas
  - pymongo
  - numpy
  - matplotlib
  - seaborn
  - pytorch
  - transformers
  - tqdm
  - wordcloud

## Getting Started

1. Clone this repository
2. Download the Yelp dataset using the link provided in the Dump folder
3. Install required dependencies
4. Run the preprocessing notebook first
5. Execute queries and sentiment analysis notebooks

## Author

Matteo Vitali

## Course Information

Systems and Methods For Big and Unstructured Data  
Politecnico di Milano  
Academic Year 2024/2025
