 Netflix Data Analysis

 Overview

This project performs Exploratory Data Analysis (EDA) on a Netflix dataset to understand trends in movies and TV shows available on the platform. The analysis focuses on content distribution, release trends, genres, ratings, and key contributors such as directors and actors.

The project uses Python data analysis and visualization libraries to uncover insights from the dataset.

---

 Dataset

The dataset used in this project:

* File: `netflix_titles.csv`
* Contains information about Netflix content including:

  * Title
  * Type (Movie / TV Show)
  * Director
  * Cast
  * Country
  * Release Year
  * Rating
  * Duration
  * Genre (`listed_in`)

---

 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

 Project Workflow

 1. Data Loading

The dataset is loaded using Pandas.

 2. Data Cleaning

Missing values are handled for important fields such as:

* Country
* Director
* Cast

Missing values are replaced with `"Unknown"` where necessary.

 3. Exploratory Data Analysis

The following analyses are performed:

 Content Distribution

* Comparison of Movies vs TV Shows available on Netflix.

 Release Trends

* Number of titles released over the years.

 Top Countries

* Countries producing the most Netflix content.

 Ratings Distribution

* Distribution of audience ratings across titles.

 Popular Genres

* Most common genres available on Netflix.

 Movie Duration Analysis

* Distribution of movie durations.

 TV Show Seasons

* Number of TV shows by season count.

 Top Contributors

* Top directors with the most titles.
* Most frequently appearing actors.

---

 Visualizations

The project includes multiple visualizations such as:

* Bar charts
* Line charts
* Horizontal bar plots
* Histograms

These help illustrate trends and patterns within the Netflix catalog.

---

 Project Structure

```
Netflix-Analysis/
│
├── Netflix Analysis.ipynb    Main Jupyter notebook
├── netflix_titles.csv        Dataset
└── README.md                 Project documentation
```

---

 How to Run the Project

 1. Clone the repository

```
git clone https://github.com/yourusername/netflix-analysis.git
cd netflix-analysis
```

 2. Install required libraries

```
pip install pandas numpy matplotlib seaborn
```

 3. Run the notebook

```
jupyter notebook
```

Open Netflix Analysis.ipynb and run the cells.

---

 Key Insights

Some insights explored in this analysis include:

* Netflix contains more movies than TV shows.
* Content releases increased significantly in recent years.
* Certain countries dominate Netflix content production.
* Some genres appear significantly more than others.

---

 Future Improvements

Possible extensions for this project:

* Build a Netflix recommendation system
* Perform sentiment analysis on reviews
* Create an interactive dashboard using Streamlit or Power BI
* Apply machine learning for content prediction 
