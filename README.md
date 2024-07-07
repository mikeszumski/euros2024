# AI BOOTCAMP GROUP PROJECT (Project 2) _DRAFT_
This repository shares the source data, examination approach, data analytics script and predictions for the Euro 2024 national teams soccer competition in Germany during the spring/summer of 2024.

## EXECUTIVE SUMMARY

### Project Objectives
To use past match results to predict top finishers in the Euro 2024 competition

### Data Analysis
The investigating team narrowed its efforts on the collection, transformation, analysis and visualization of results of national team matches leading up to the Euro2024 competition.  
- Unsupervised learning models were used to identify key groupings of team performances in competitions leading up to the Euro2024 competion.  These matches included qualifying matches, the UEFA league competition during 2022 and 2023, as well as many international friendlies during 2023.
- Supervised learning models were employed to predict top finishers in the competition.

We conducted data discovery activites, including:
* Data Identification and Exploration –  identified and reviewed available datasets, screening for data applicability and data quality
* Data Transformation – imported, cleaned and joined datasets by location and date attributes or disaster ID.  
* Data Analysis – explored the relationship of the various datasets, evaluated the relative impact of features, and evaluated several machine learning models.

### Summary Findings
Analyses exposed the difficulty of using past performance to predict future results in the sphere of national mens soccer.

## ANLYSIS DETAILS

### Datasets Analyzed
The team collected fundamental data - detailed match results - and combined that with a measure frequently used in soccer statistics - Expected Goals (xG), and betting odds.

__International Mens Match Results__
* [Football - Soccer - UEFA EURO, 1960 - 2024](https://www.kaggle.com/code/mahmoudredagamil/football-soccer-uefa-euro-1960-2024)

__Expected Goals (xG)__
* [xG Stats for Football Teams](https://footystats.org/stats/xg)

__Odds__
* [Euro 2024 Winner Odds - Outright betting](https://www.oddsportal.com/football/europe/euro-2024/outrights/)



### Data Analysis Using Python
The team developed the __filenamehere.ipynb__ python notebook to ingest, explore, transform, visualize and merge the datasets. Once merged, the investigating team analyzed a dataframe consisting of xxxx...

### Analysis Results


__Key Observations__ 
* Obs 1
* Obs 2

__Key Analysis Findings__
* finding 1
* finding 2

### Conclusion
write conclusion here

Given access to higher fidelity public health data and additional time to explore more public data, the investigating team may have opted to explore the following areas:
* next steps
* next steps

### Project Contributors
* Kurt Andresson | [GitHub_@kurtadresson](https://github.com/kurtandreassen)
* Maggie Rosen | [GitHub_@MaRos3n](https://github.com/maggierosen/)
* Michael Szumski | [GitHub @mikeszumski](https://github.com/mikeszumski/)

## Other Acknowledgments
* Project instruction and requirements provided by [The Artificial Intelligence Boot Camp at UNC Charlotte](https://bootcamp.charlotte.edu/artificial-intelligence/)

## Repo Contents
* corrected_euro_team_data.csv - Working excel sheet with combined data joined into a single sheet. Unneeded columns removed. 
* Euro_team_data_revised_v4.ipynb - Data cleanup code.  Reshaped data from matches to teams/matches, add score_differential field, convert match date to datetime, drop unnecessary fields, one-hot encode string fields, 
