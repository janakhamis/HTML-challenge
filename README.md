# Mars Data Analysis Project

## Overview
This project involves two parts: extracting and analyzing data related to Mars using Python. In Part 1, we scraped news titles and previews from the Mars News website. In Part 2, we extracted, analyzed, and visualized Mars weather data.

## Part 1: Scraping Mars News Titles and Previews
1. **Automated Browsing:**
   - Utilized Splinter to automate browsing and retrieve HTML content with Beautiful Soup.
2. **Data Extraction:**
   - Scraped news titles and preview texts.
   - Stored the data as a list of dictionaries, each containing the title and preview.

## Part 2: Scraping and Analyzing Mars Weather Data
1. **Data Extraction:**
   - Scraped a Mars weather table using Pandas and Beautiful Soup.
   - Converted the table into a Pandas DataFrame with proper headers and data types.
2. **Analysis:**
   - Identified 12 Martian months and the total number of Martian days (sols) in the dataset.
   - Analyzed trends in:
     - **Temperature:** Found months with the lowest and highest average minimum temperatures.
     - **Pressure:** Identified months with the lowest and highest atmospheric pressure.
     - **Year Length:** Estimated a Martian year as approximately 687 Earth days through a temperature trend plot.
3. **Data Export:**
   - Saved the cleaned DataFrame as a CSV file.

## Tools
- Python libraries: Splinter, Beautiful Soup, Pandas, Matplotlib.

## How to Run
  1. Clone the repository:
       1. Open your terminal (Git Bash, Command Prompt, or any Git client).
       2. Use the cd command to navigate to the directory where you want to clone the repository.
       3. Run the following command to clone the repository: git clone link_provided
  2. Ensure Splinter, Beautiful Soup, Pandas, and Matplotlib is installed on your machine.
     - Install Splinter using pip if it's not already installed (pip install splinter).
     - Install Beautiful Soup using pip if it's not already installed (pip install bs4).
     - Install Pandas using pip if it's not already installed (pip install pandas).
     - Install Matplotlib using pip if it's not already installed (pip install matplotlib).
  3. Open the cloned file in the Visual Studio Code:
       1. Go to file > Open Folder and navigate to the folder where you cloned the repository.
       2. Select the folder to open in VS code.
  4. Run the Jupyter Notebook
     1. Open the notebook file (part_1_mars_news.ipynb & part_2_mars_weather.ipynb) in VS code or Jupyter.
     2. Run the cells to perform the Analysis.
