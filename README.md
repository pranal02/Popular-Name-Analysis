# Popular-Name-Analysis
# Overview
-This project analyzes popular baby names in the United States using data provided by the Social Security Administration (SSA). It involves extracting data from a ZIP file, manipulating the data using pandas, and --visualizing trends using Seaborn and Matplotlib. The main objectives are:

- Visualize the number of male and female babies born in a particular year.
- Identify and analyze the most popular baby names over the years.
- Dataset
# The dataset used in this project includes data from the SSA on baby names, with details such as:

- Name: Baby's name
- Gender: Gender of the baby (Male/Female)
- Count: Number of babies born with that name in a particular year
- Year: Year of birth
# Download the Dataset
- Go to the SSA Baby Names Page.
- Click on 'National data' and download the ZIP file containing the dataset.
- Place the downloaded names.zip file in the project directory.
# Analysis Steps
# 1. Data Extraction
- The dataset is extracted from the ZIP file using the zipfile and io libraries.
- All files containing baby name data are read into a single pandas DataFrame.
# 2. Data Visualization
- The number of male and female babies born each year is visualized using a bar plot.
- The count of male and female babies is displayed on top of each bar for better understanding.
# 3. Popular Baby Names
- The dataset is analyzed to identify the most popular baby names over the years.
- The top 10 most popular names are visualized using a bar plot.
