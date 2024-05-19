# AirBnB-Amsterdam-Listing-Analysis

## Tools
Python 3.0 was used for the cleaning, wrangling, and initial visual exploration and analysis. Tableau was used for final visualizations
Tableau Public Dashboard built with data here: https://public.tableau.com/app/profile/nuno.marques1822/viz/AirBnBAmsterdamlistinganalysisproject/Story1 

## Introduction
Over the course of the past decade, local short-term housing rental services like AirBnB have grown exponentially, becoming an alternative avenue for those seeking a more local and private stay than a traditional hotel can offer. Nowadays, it is common for people to utilize this alternative service to generate additional income by investing in rental properties. However, the rental market is highly region and time-specific, and committing to investing in a rental property is a high-risk decision. This project aims to better understand the Amsterdam AirBnB market to provide insights for prospective AirBnB hosts who have or want to have listings in Amsterdam and want to be informed about general characteristics and trends of listings.

## Data Source discussion
### Source: insideairbnb.com, a mission-driven activist project with the objective to provide data that quantifies the impact of short-term rentals on housing and residential communities, as well as create a platform to support advocacy for policies to protect our cities from the impacts of short-term rentals. They collect publicly available data from AirBnB’s website and analyse it themselves
#### Data Sourcing:
The data comes from Kaggle project Airbnb Amsterdam. This project used data from the website insideairbnb.com . Inside Airbnb is a mission-driven activist project with the objective to provide data that quantifies the impact of short-term rentals on housing and residential communities, as well as create a platform to support advocacy for policies to protect our cities from the impacts of short-term rentals.
#### Data Collection:
The data behind the Inside Airbnb site is sourced from publicly available information from the Airbnb site. The data has been analyzed, cleansed and aggregated to facilitate public discussion. 
#### Data Contents:
Data Dictionary: https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit#gid=1322284596 

The dataset contains information on all the AirBnB listings in Amsterdam on December 6th, 2018 (20k).
calendar.csv contains the status of occupancy for all listings for the following year after December 6th, 2018.
listings_details.csv contains information on listings such as host id and name, listing id and description, neighbourhood, price, geographical location, etc…


## Folder Structure
* 01 Project Management: Project brief
* 04 Analysis: The Visualizations subfolder contains the visualizations used for developing and explaining insights.
* 03 Scripts: Jupyter notebooks used for analysis and visualizations
* Prepared Data contains the clean and wrangled data
* listings_details and calendar are the original datasets used.
