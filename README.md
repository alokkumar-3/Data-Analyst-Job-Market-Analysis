# Data Analyst Job Market Analysis

## Project Overview
This project provides an end-to-end analysis of the Data Analyst job market using a dataset of job postings. The workflow starts by fetching raw data from a MySQL database, followed by a rigorous cleaning and preprocessing phase. Finally, an extensive exploratory data analysis (EDA) is conducted, with visualizations created to uncover key insights into salary distributions, in-demand skills, top locations, and industry trends.

## Objectives
* Analyze the overall salary distribution for Data Analyst positions.
* Identify the most common and the highest-paying Data Analyst job titles.
* Determine the top geographical locations for both job opportunities and high salaries.
* Investigate the impact of company size and ownership type on average salary.
* Pinpoint the key industry sectors that are actively hiring Data Analysts and their salary benchmarks.

## Tools & Technologies
-   **Python:** Core language for data processing and analysis.
-   **Pandas & NumPy:** For data manipulation, cleaning, and numerical operations.
-   **Matplotlib & Seaborn:** For creating static and interactive visualizations.
-   **SQLAlchemy:** To connect to and retrieve data from the MySQL database.

## Key Insights
-   The most frequent job titles are **Data Analyst**, **Senior Data Analyst**, and **Junior Data Analyst**.
-   Top-paying locations are heavily concentrated in **California** (Newark, Marin City) and **Illinois** (Northfield, Glenview).
-   **New York**, **Chicago**, and **San Francisco** are the top three cities with the most job openings for data analysts.
-   Companies with **5001 to 10000 employees** tend to offer the highest average salaries.
-   While **Information Technology** and **Business Services** are the largest employers, the **Biotech & Pharmaceuticals** sector offers the highest average salaries.

## Project Structure
-   `1. cleaning DA Jobs Project.ipynb`: Connects to the database, cleans the data, and parses salary information.
-   `2. DA Jobs Exploration.ipynb`: Conducts further cleaning on job titles and initial data exploration.
-   `3. DA jobs Viz.ipynb`: Contains the code for generating all final plots and visualizations.
-   `jobs_cleaned`: The cleaned dataset (in pickle format) passed between notebooks.

## How to Use
1.  **Database Setup:** Load the raw job data into a MySQL database named `DA_jobs` under a table called `jobs_table`.
2.  **Update Connection:** Modify the SQLAlchemy connection string in `1. cleaning DA Jobs Project.ipynb` with your database credentials.
3.  **Install Libraries:** Install the required Python packages.
    ```bash
    pip install pandas numpy matplotlib seaborn sqlalchemy mysql-connector-python
    ```
4.  **Run Notebooks:** Execute the Jupyter Notebooks in chronological order: `1. cleaning DA Jobs Project.ipynb`, `2. DA Jobs Exploration.ipynb`, and finally `3. DA jobs Viz.ipynb`.


---
**License:** This project is for educational purposes.
