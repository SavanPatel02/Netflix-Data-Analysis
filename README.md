-----

# 🍿 Netflix Data Analysis & Visualization 📊

Welcome to the Netflix Data Analysis project\! This repository contains a Jupyter Notebook (`Netflix.ipynb`) that performs a deep dive into the Netflix movies and TV shows dataset.

The analysis cleans, explores, and visualizes trends in content type, ratings, release years, popular genres, and top directors.

## 📈 Analysis & Key Insights

This notebook performs a full Exploratory Data Analysis (EDA) pipeline:

  * **📦 Data Loading:** Imports the `netflix1.csv` dataset.
  * **🧹 Data Cleaning:**
      * Checks for duplicates and missing values.
      * Converts date columns to the proper `datetime` format.
  * **✨ Feature Engineering:**
      * Extracts `year`, `month`, and `day` from the `date_added` column.
  * **📊 Exploratory Data Analysis:**
      * Analyzes the distribution of **Movies vs. TV Shows**.
      * Visualizes the most common **content ratings** (e.g., TV-MA, PG-13).
      * Identifies the **Top 10 countries** producing content.
      * Plots content addition trends by **year and month**.
      * Determines the most popular **genres** for both movies and TV shows.
      * Finds the **Top 10 directors** on the platform.
      * Generates a **word cloud** from content titles.

## 🎨 Visualizations Generated

Running the notebook will automatically save 11 high-quality visualizations (and 2 data files) to your directory, ready to be used in any report:

```
📁 Generated Files:
│
├── 📄 netflix_cleaned_data.csv        # The cleaned dataset
├── 📄 netflix_summary_report.csv      # Summary statistics
│
├── 📈 1_content_type_distribution.png   # Pie chart
├── 📈 2_rating_distribution.png       # Bar chart
├── 📈 3_top_countries.png            # Bar chart
├── 📈 4_yearly_releases.png          # Line chart
├── 📈 5_monthly_releases.png         # Bar chart
├── 📈 6_movie_genres.png              # Bar chart
├── 📈 7_tv_show_genres.png           # Bar chart
├── 📈 8_top_directors.png             # Bar chart
├── 📈 9_release_year_distribution.png  # Histogram
├── 📈 10_movie_wordcloud.png         # Word cloud
└── 📈 11_day_distribution.png        # Bar chart
```

## 🛠️ Tech Stack

This project uses standard Python data science libraries:

  * `pandas`
  * `numpy`
  * `matplotlib`
  * `seaborn`
  * `wordcloud`

## 🚀 How to Run

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/YourUsername/YourRepositoryName.git
    cd YourRepositoryName
    ```

2.  **Install dependencies:**

    ```bash
    pip install pandas numpy matplotlib seaborn wordcloud
    ```

3.  **Get the data:**

      * You must provide your own copy of the `netflix1.csv` dataset.
      * Place it in the same directory as the notebook.

4.  **Run the notebook:**

      * Open and run the `Netflix.ipynb` notebook in Jupyter Notebook, Jupyter Lab, or Google Colab.

-----
