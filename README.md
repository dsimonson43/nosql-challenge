# nosql-challenge
# Overview
#This project works to analyze food hygiene ratings across the United Kingdom using MongoDB. The data is derived from the UK Food Standards Agency. The goal is to assist the editors of the "Eat Safe, Love" magazine to identify trends in food establishments and highlight concerns within the industry. 
# Project Objectives
1. Setup the Database
   - establishments.json was imported to MongoDB
   - verification of database structure and collections
2. Updating Database
   - Added new establishment (Penang Flavours)
   - Updated missing BusinessTypeID values
   - Removed all establishments from the city of Dover
   - Converted latitude, longitude, and RatingValue to numeric data types
3. Exploratory Analysis
   - identified establishments with a recorded hygiene score of 20
   - queried for highly-rated establish
   - located the top 5 highest rated restaurants near Penang Flavours
   - determined the worst local authories according to hygiene scores
# Technologies Used
- Python + Jupyter Notebook
- MongoDB (NoSQL Database)
- PyMongo (MongoDB Python Driver)
- Pandas (analysis)
# Usage
To run this project...
1. Install MongoDB
2. Import dataset into MongoDB using compass
3. Open NoSQL_setup_starter.ipynb
4. Run the queries in NoSQL_analysis_starter.ipynb
