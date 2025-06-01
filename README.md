# Summer Analytics 2025: Data Analysis Assignment

## Project Overview

This repository contains the solution to the first Data Analysis Assignment for the Summer Analytics 2025 program. The assignment focuses on using Python's data analysis libraries (Pandas, NumPy) and visualization tools (Matplotlib, Seaborn) to explore and derive insights from a dataset of car specifications.

The assignment was completed using Google Colab.

## Dataset

The dataset used for this assignment is `Cars.csv`, which contains various attributes of different car models, including:
- `mpg` (miles per gallon)
- `cylinders`
- `displacement`
- `horsepower`
- `weight`
- `acceleration`
- `model_year`
- `origin`
- `name`

## Assignment Tasks & Solutions

The `Summer Analytics 2025 - Assignment.ipynb` notebook in this repository contains the detailed solutions to the assignment questions. Key tasks covered include:

* **Data Loading and Inspection:** Reading the CSV file into a Pandas DataFrame, displaying its shape, columns, and basic statistics.
* **Data Manipulation:** Setting specific columns as the DataFrame's index.
* **Data Querying:** Retrieving unique values and filtering data based on conditions.
* **Feature Engineering:** Creating new metrics from existing columns.
* **Graded Questions:**
    * Identifying the car with the highest horsepower.
    * Counting cars with specific `mpg` thresholds.
    * Finding the most common origin based on combined criteria (horsepower, weight).
    * Calculating the mean acceleration for cars from a specific origin.
    * Determining the year with the highest average `mpg`.
* **Ungraded Questions (Extra Exercise):**
    * Identifying car models with the best horsepower-to-weight ratio among those with above-median `mpg`.
    * Designing a multi-line plot to show the evolution of average `mpg` by origin over years.
    * Creating a Seaborn scatterplot to visualize relationships between `horsepower`, `weight`, `origin`, and `mpg`.
    * Identifying "consistent" car models (low `mpg` variation across multiple production years).

## How to Run the Notebook

You can run this notebook directly in Google Colab:

1.  **Open in Google Colab:** Click on the `Summer Analytics 2025 - Assignment.ipynb` file in this GitHub repository. On the GitHub page, you should see an "Open in Colab" button (or you can copy the URL and open it via `File > Open notebook > GitHub` in Colab).
2.  **Upload the Dataset:** Once the notebook is open, you will need to upload the `Cars.csv` file to your Colab session.
    * Click the folder icon (Files) on the left sidebar.
    * Click the "Upload to session storage" icon (up-arrow into a cloud).
    * Select the `Cars.csv` file from your local computer (you would have downloaded this along with the `.ipynb` from the assignment source).
3.  **Run the Cells:** Execute each code cell sequentially. Ensure the `Cars.csv` file is loaded into the `df_original` DataFrame as instructed in the notebook.

## Technologies Used

* **Python 3**
* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical operations.
* **Matplotlib:** For basic plotting.
* **Seaborn:** For enhanced statistical data visualization.
* **Google Colab:** Cloud-based Jupyter Notebook environment.

