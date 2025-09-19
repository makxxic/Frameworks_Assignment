# Frameworks_Assignment
plp python week8 assignment
# CORD-19 Metadata Analysis

## Overview
This project analyzes the `metadata.csv` file from the CORD-19 dataset.  
It explores COVID-19 research publications by year, journal, and title keywords.  
The project also includes a **Streamlit app** for interactive visualization.

## Reflection
Learned to handle missing values and datetime formats.
Gained practice in word frequency visualization.
Built an interactive Streamlit dashboard.

## Tools
- Python 3.7+
- pandas, matplotlib, seaborn
- wordcloud
- streamlit
- jupyter

## 📥 Dataset Download
We use only the **`metadata.csv`** file from the CORD-19 dataset.
1. Go to the Kaggle dataset page:  
   👉 [CORD-19 Research Challenge](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge)
2. Download the `metadata.csv` file.
3. Place the file inside the `data/` folder of this project:

## Steps
1. Load and clean metadata.csv
2. Explore publications by year and journal
3. Generate visualizations
4. Deploy a Streamlit app

## Run Streamlit App
```bash
streamlit run app.py

