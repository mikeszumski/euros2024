# AI BOOTCAMP GROUP PROJECT (Project 2)
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
* [International football results from 1872 to 2024](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017?resource=download)

__Expected Goals (xG)__
* [xG Stats for Football Teams](https://footystats.org/stats/xg)

__Odds__
* [Euro 2024 Winner Odds - Outright betting](https://www.oddsportal.com/football/europe/euro-2024/outrights/)

### Data Analysis Using Python
The team developed the __filenamehere.ipynb__ python notebook to ingest, explore, transform, visualize and merge the datasets. Once merged, the investigating team analyzed a dataframe consisting of xxxx...

### Conclusion
Best feature in our models for predicting the winners, are team odds.  These were collected from betting sites, and we in effect confirmed that they're a good indicator of success.  
Using past performance to predict future success in mens soccer is a difficult business as our work with the models showed.  Good for the game that outcome is subject to many many factors, but difficult for those of us who try to pick winners.

Given access to higher fidelity player and team data and additional time to explore more data data, the investigating team may have opted to explore the following areas:
- Reshape the data to take a view of each team involved by summarizing match level data
- Rebuild the model to treat a team as a collection of individuals and collect information about the individual team members, either starters, or both starters and substitutes.
- Include additional features, such as manager experience, days since last match, some measure of player health, and referee.
- Incorporate additional teams performance data from the tournament itself, as each game is played.

### Project Contributors
* Kurt Andresson | [GitHub_@kurtadresson](https://github.com/kurtandreassen)
* Maggie Rosen | [GitHub_@MaRos3n](https://github.com/maros3n/)
* Michael Szumski | [GitHub @mikeszumski](https://github.com/mikeszumski/)

## Other Acknowledgments
* Project instruction and requirements provided by [The Artificial Intelligence Boot Camp at UNC-Chapel Hill](https://bootcamp.unc.edu/artificial-intelligence/)

## Repo Contents
* Project_2_EUROS_Predictions_Deck.pdf - Full presentation of project content.
* corrected_euro_team_data.csv - Cleaned data for the machine learning models.
* Euro_team_data_revised_v6.1.ipynb - Jupyter notebook containing all elements of the analysis.

1. Data cleanup code
2. Unsupervised machine learning code
3. Supervised machine learning code
4. Predictions 
