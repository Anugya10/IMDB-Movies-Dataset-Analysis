# IMDB-Movies-Dataset-Analysis

In this Python data analysis project, the IMDB Movie Dataset is explored to derive insights into various movie aspects. Essential Python libraries such as Pandas, and Matplotlib are employed for efficient data manipulation and visualization.

**Dataset Overview:**

The dataset consists of 1000 entries, each representing a movie, featuring 12 columns providing information such as title, genre, director, year, runtime, rating, votes, revenue, and metascore.

**Data Cleaning:**

The initial step involves checking the dataset's shape, revealing 1000 rows and 12 columns. The identification of missing values, visualized through a heatmap, prompts their removal to ensure data integrity.

**Handling Duplicates:**

Duplicate entries are examined and removed to enhance the dataset's clarity and avoid redundancy.

**Exploratory Data Analysis (EDA):**

EDA is conducted to unveil patterns and trends. It includes displaying overall statistics, identifying lengthy movies, determining the highest average voting and revenue per year, and assessing the rating's impact on revenue.

**Top Movies Analysis:**

The identification of the most popular movies based on revenue and highest ratings is performed. Additionally, movies are classified into categories like "Excellent," "Good," or "Average" based on their ratings.

**Genre Analysis:**

An exploration of genre information involves counting the number of action movies and finding unique genre values.

List of functions used in the "IMDB Movie Dataset Data Analysis" project:

**Pandas Functions:**

pd.read_csv(): Reads the dataset from a CSV file.
isnull().sum(): Counts the missing values in the dataset.
dropna(): Drops rows with missing values.
duplicated().any(): Checks for duplicate rows.
describe(include='all'): Provides overall statistics about the dataframe.
**
Matplotlib Functions:**

plt.figure(figsize=(width, height)): Sets the figure size for plots.
plt.title(): Adds a title to the plot.
plt.show(): Displays the plot.
