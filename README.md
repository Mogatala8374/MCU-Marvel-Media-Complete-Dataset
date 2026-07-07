
# Marvel Cast Dataset - Exploratory Data Analysis (EDA)

## Project Overview
 
This project performs **Exploratory Data Analysis (EDA)** on the **Marvel Cast Dataset** using Python. The objective is to clean, analyze, and visualize the dataset to discover meaningful patterns related to Marvel movies, actors, cast order, and popularity. The project demonstrates the complete EDA workflow, including data wrangling, statistical analysis, and data visualization.

---

## Objectives

* Understand the structure of the Marvel Cast Dataset.
* Clean and preprocess the dataset.
* Handle missing values and duplicate records.
* Perform exploratory data analysis using statistical summaries.
* Visualize trends and relationships between variables.
* Generate insights that support data-driven decision-making.

---

## Dataset Description

The dataset contains information about Marvel movies and their cast members. It includes the following attributes:

| Column Name   | Description                            |
| ------------- | -------------------------------------- |
| title         | Name of the Marvel movie               |
| year          | Release year of the movie              |
| tmdb_id       | Movie ID from TMDB                     |
| actor_name    | Name of the actor                      |
| character     | Character played by the actor          |
| cast_order    | Position of the actor in the cast list |
| actor_tmdb_id | Actor ID from TMDB                     |
| popularity    | Popularity score of the actor          |
| profile_path  | Actor profile image path               |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

* Imported the Marvel Cast Dataset.
* Loaded the dataset using Pandas.

### 2. Data Wrangling

* Checked dataset dimensions and data types.
* Identified missing values.
* Removed duplicate records.
* Renamed columns for better readability.
* Converted data types where required.
* Created additional features such as:

  * Total Cast
  * Popularity Level
  * Decade

### 3. Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset Information
* Missing Value Analysis
* Duplicate Detection
* Descriptive Statistics
* Movie Releases by Year
* Top Movies by Cast Size
* Most Frequently Appearing Actors
* Popularity Distribution
* Popularity Box Plot
* Correlation Heatmap
* Average Popularity by Year
* Top Popular Actors
* Cast Order Distribution
* Most Common Characters
* Scatter Plot (Popularity vs Cast Order)
* Pair Plot

---

## Key Insights

* Marvel movie production has increased over the years.
* Some movies have significantly larger casts than others.
* A few actors appear in multiple Marvel movies.
* Actor popularity is not solely determined by cast order.
* Most actors have moderate popularity, while only a few are highly popular.
* Correlation analysis indicates a weak relationship between cast order and popularity.

---

## Business Impact

The insights obtained from this analysis can help movie production companies:

* Identify highly popular actors for marketing campaigns.
* Improve casting decisions.
* Plan future movie releases effectively.
* Optimize promotional strategies.
* Better understand audience preferences.

---

## Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## Project Structure

```
Marvel-EDA/
│
├── marvel_cast.csv
├── marvel_cast_cleaned.csv
├── Marvel_EDA.ipynb
├── README.md
└── images/
    ├── movies_per_year.png
    ├── popularity_distribution.png
    ├── top_actors.png
    ├── scatter_plot.png
    └── correlation_heatmap.png
```

---

## How to Run the Project

1. Install Python (3.9 or later).
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Place the `marvel_cast.csv` file in the project folder.
4. Open the Jupyter Notebook.
5. Run all cells sequentially to reproduce the analysis and visualizations.

---

## Future Improvements

* Build machine learning models to predict actor popularity.
* Perform sentiment analysis using movie reviews.
* Create an interactive dashboard using Plotly or Streamlit.
* Integrate additional Marvel movie datasets for deeper analysis.

---

## Conclusion

This project demonstrates how Exploratory Data Analysis (EDA) can transform raw data into meaningful insights. Using Pandas, NumPy, Matplotlib, and Seaborn, the project successfully cleans, explores, and visualizes the Marvel Cast Dataset. The findings reveal trends in movie releases, actor popularity, cast distribution, and production patterns, providing valuable information that can support informed business decisions and future analytical studies.
