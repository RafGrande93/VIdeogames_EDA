# Video Games: An Exploratory Data Analysis

Video Games: An Exploratory Data Analysis
==============================

Overview
--------
This project contains a Jupyter notebook (`Video_Games_Analysis.ipynb`) where we perform an **exploratory data analysis (EDA)** on a dataset of video games.

The notebook walks step by step through:
1. **Loading and cleaning the dataset**
   - Importing the required Python libraries (pandas, matplotlib).
   - Reading the dataset into memory and cleaning it.

2. **Exploring the data**
   - Summarizing statistics for sales by using mean, median, standard deviation and quartiles.
   - Checking for outliers (i.e. the best sellers)

3. **Visualizing the data**
   - Plotting the distribution of global sales.
   - Visualizing top-performing genres, platforms and consoles.
   - Identifying sales by region.

4. **Drawing conclusions**
    -There are few best seller videogames
    - Nintendo and Sony are really successful, even though Microsoft has the second best selling console
    - Some ideas for third party studios

How to Use
----------
1. Install dependencies:

   pip install -r requirements.txt

2. Open the notebook in Jupyter:

   jupyter notebook Video_Games_Analysis.ipynb

3. Run the cells in order (from top to bottom) to reproduce the analysis.

Structure
----------

├─ README.md
├─ requirements.txt
├─ Video_Games_Analysis.ipynb
├─ Video_Games.csv
├─ License.txt


Notes
-----
- Place the dataset in the same directory as the notebook (or update file  paths inside the code).
- If additional libraries are installed later, update `requirements.txt`.
