#Netflix Shows and Movies Data Analysis

Overview:
This project involves the analysis of a Netflix dataset that includes information on various shows and movies. The analysis is performed using Python for data preparation, cleaning, exploration, and visualization. Additionally, one of the visualizations is integrated into R. The steps in this project include:
•	Data Preparation: Unzipping the dataset and renaming it for clarity.
•	Data Cleaning: Handling missing values in columns such as director, cast, country, date_added, and rating.
•	Data Exploration: Generating descriptive statistics and exploring unique values in columns like type, rating, and listed_in (genres).
•	Data Visualization: Creating visualizations to showcase the top 10 most common genres and the distribution of content ratings.
•	R Integration: Implementing one of the Python-generated visualizations in R using the ggplot2 package.
All project files are provided to allow replication in your environment. Detailed instructions for accessing and running the code are provided below.
________________________________________
Files Included
1.	Netflix Data Analysis.ipynb: A Jupyter notebook containing the Python code for data preparation, cleaning, exploration, and visualization. You can open and run this notebook to replicate the steps in Python.
2.	README.txt: This file, offering a detailed overview of the project, including instructions on accessing and interpreting the code.
3.	R Visualization Code.R: An R code that plots a graph showing top 10 genres in the dataset
4.  netflix_data.csv: This is the dataset used by the jupyter notebook
________________________________________
Instructions

1. Requirements
To run the code in this project, ensure that the following Python packages are installed:
	•	pandas: For data manipulation and analysis.
	•	matplotlib: For data visualization.
	•	seaborn: For enhanced data visualization.
For R integration, the following packages are required:
	•	ggplot2: For creating visualizations in R.
	•	readr: For reading CSV files in R.

2. Running the Python Code
Step 1: Data Preparation and Cleaning
	•	Open the "Netflix Data Analysis.ipynb" file in Jupyter Notebook.
	•	Follow the steps outlined in the notebook to:
		o	Load and rename the dataset.
		o	Handle missing values in key columns.
		o	Explore the dataset using basic statistics and counts.
Step 2: Data Exploration and Visualization
	•	Continue running the notebook to:
		o	Generate descriptive statistics.
		o	Create bar plots for the top 10 most common genres and the distribution of ratings using Python libraries (matplotlib and seaborn).
Step 3: Saving the Cleaned Dataset
	•	The cleaned dataset is saved as Netflix_shows_movies_cleaned.csv. This file is included for further use in R.

3. Running the R Code in Visual Studio
If you're using Visual Studio to run R, follow these steps:
Step 1: Install Required Libraries
	•	In the Terminal or Console, install the required R libraries
Step 2: Load the Cleaned Dataset
	•	Load the cleaned dataset (Netflix_shows_movies_cleaned.csv) into R
Step 3: Create a Visualization in R
	•	Use ggplot2 to create a bar chart for the top 10 most common genres. The R code for this is provided in the project.



