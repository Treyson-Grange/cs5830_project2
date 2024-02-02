# Austin Crime Report 2015 Data Analysis Project 2

## Project Overview
The goal of this project is to analyze the Austin Crime Housing 2015 dataset using Pearson Correlation Tests, scatterplots, averages, standard deviations, and t-tests. 

## Dataset Description
The Austin Crime Housing 2015 dataset represents an amalgamation of two distinct data sources. It integrates the Annual Crime Dataset 2015 from austintexas.gov, which details all Part 1 crimes recorded in Austin, Texas, spanning the duration of January 1 to December 31, 2015. And has been merged with the 2014 Housing Market Analysis Data by Zip Code, extracted from the City of Austin's 2014 Comprehensive Housing Market Analysis. This latter dataset provides a detailed overview of demographic and housing-related information for each zip code within Austin. Together, these datasets present a varied view of Austin's crime and housing landscape in 2015.

## File Structure
- `project2.ipynb`: Jupyter notebook containing the analysis code.
- `crime-housing-austin-2015.csv`: The dataset file containing crime housing statistics for austin in 2015 (It must be provided by the user).
- `AustinZipCodes.csv`: The dataset gives population densities that can assist in getting crime per capita (It must be provided by the user).
- `requirements.txt`: List of Python dependencies required for this project.

## Installation
To set up the project environment:
1. Clone the repository or download the project files.
2. Install Python (version 3.x or above) and Jupyter Notebooks.
3. Run `pip install -r requirements.txt` to install required Python packages.
4. Add a `datasets` folder to the main directory. 
5. Add in the `crime-housing-austin-2015.csv` to the `datasets` folder in the main directory. 
6. Add in the `AustinZipCodes.csv` to the `datasets` folder in the main directory. 

## Usage
- Open the `project2.ipynb` file in Jupyter Notebook or VS code to view the analysis.
- The notebook is divided into sections, each focusing on a different aspect of the data analysis.
- You can modify and rerun the code cells to explore different hypotheses or perspectives.

## Analysis Techniques 
1. Distribution of rapes by Zip Code
2. Bulgary success rate compared to Median Household Income
3. Rental units affordable to an average teacher and the frequency of crime types in those Council Districts
    - Averages
    - Scatter plots
    - Pearson Correlation Test
4. Crime Statistics by Zip Code
    - Bar & Box plots
    - Means
    - T-test

Each technique is demonstrated with appropriate visualizations using Seaborn and/or Matplotlib.