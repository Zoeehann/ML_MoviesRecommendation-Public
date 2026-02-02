# Movie Recommendation & Prediction System

**Project Overview**

This is a comprehensive machine learning project that combines multiple recommendation and prediction techniques for movies. The project analyzes The Movies Dataset (TMDb) and implements various ML algorithms to create a robust recommendation system.


## Files Included
**1. Movie_Recommendation_System_Complete.ipynb**

The main Jupyter notebook containing all analysis and models
Combines content from both original notebooks
Well-organized with clear sections and documentation
Includes visualizations and model evaluations

**2. movie_recommendation_system.py**

Python script version for easy execution
Contains all code from the notebook
Can be run directly or imported as a module


## Project Structure
**1. Data Loading & Exploration**

- Load all CSV files
- Initial data inspection
- Understanding data structure


**2. Descriptive Analysis**

Movies Metadata Analysis
- Statistical summaries
- Distribution of budget, revenue, popularity
- Genre analysis
- Release date patterns
  
Credits Analysis
- Cast and crew information
- Most frequent actors/directors
  
Ratings Analysis
- User rating distributions
- Rating patterns over time
  

**3. Data Preprocessing**

Data Cleaning
- Handling missing values
- Removing duplicates
- Data type conversions

Feature Engineering
- Extracting genres from JSON strings
- Processing keywords
- Creating new features

Text Processing
- Combining relevant text features
- Tokenization and cleaning


**4. Machine Learning Models**
   
Content-Based Filtering
- TF-IDF Vectorization: Convert movie descriptions and metadata into numerical vectors
- Cosine Similarity: Measure similarity between movies
- Recommend similar movies based on content

Collaborative Filtering
- User-based recommendations
- Item-based recommendations
- Using rating patterns

Predictive Models
- Decision Trees: For classification/prediction tasks
- Support Vector Machines (SVM): For pattern recognition
- Model evaluation using appropriate metrics
