# Project Overview
This project is part of my **IBM Data Science Capstone**. The goal is to predict whether the **Falcon 9 first stage** will successfully land after launch. Since SpaceX can reuse boosters, accurate landing predictions help estimate launch costs and assess commercial competitiveness.

## Key Steps
The project is divided into multiple notebooks, each focusing on a stage of the data science pipeline:

### Data Collection
- **data_collection_api.ipynb** - Collected data from SpaceX API.  
- **data_collection_webscraping.ipynb** - Scraped launch records from Wikipedia.

### Data Wrangling
- **data_wrangling.ipynb** - Cleaned and transformed datasets for analysis.

### Exploratory Data Analysis
- **eda_sql.ipynb** - Queried the dataset using SQL for insights.  
- **eda_visualizations.ipynb** - Created visualizations to explore correlations and landing outcomes.

### Interactive Visualizations
- **interactive_folium.ipynb** - Built maps to visualize launch sites and trajectories.  

### Machine Learning Prediction
- **machine_learning_prediction.ipynb** - Built and tuned classification models (**Logistic Regression, SVM, Decision Trees, K-Nearest Neighbors**) to predict landing success.

## Tools & Libraries
- Python (**Pandas, NumPy, Scikit-learn**)  
- SQL  
- Matplotlib, Seaborn, Folium 
- Jupyter Notebooks

## Results
- Identified factors influencing Falcon 9 first stage landing success.  
- Developed predictive models.  
- Created an interactive dashboard for stakeholders to explore results.
