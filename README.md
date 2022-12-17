# j233-proj-trees-in-sf
This is the final project for J233: Advanced Coding at UC Berkeley Graduate School of Journalism in Fall 2022, taught by Soo Oh. 

I cleaned and analyzed the street tree list dataset to explore the trees in San Francisco. Using Python / pandas, altair and other packages, I answered the following questions:
1. In which year are most trees in San Francisco planted?
2. What's the most common tree species in San Francisco?
3. Where are street trees planted in the city? 

## About the dataset

**Name:** [Street Tree List]('https://data.sfgov.org/City-Infrastructure/Street-Tree-List/tkzw-k3nq') from DataSF.com portal  
**Source:** San Francisco Department of Public Works  
**Data Dictionary:** See [here](https://data.sfgov.org/api/views/tkzw-k3nq/files/biK1RHNRcrlnB42VCsuvdib3tybKjazIH4kuDcrOczw?download=true&filename=DPW_DataDictionary_Street-Tree-List.pdf)  
**Time:** Downloaded on Nov. 6, 2022. Dataset created in Sep. 24 2012 and updated daily.  

## About the repo

**There are three notebooks in this repo:**
- `00_pitch`: the initial project pitch filed on Oct. 31
- `01_data_cleaning`: importing and prepping the data for analysis
- `02_data_analysis`: analysis based on the dataset

**Data files**
- `map`: SF shapefiles
- `raw-data`: a copy of the original dataset
- `street_tree_list.csv`: the dataset that I imported and used in this repo
- `sf_trees_clean.csv`: the cleaned dataset

**Other files**
- README.md
- requirements-3.9.4.txt
- LICENSE