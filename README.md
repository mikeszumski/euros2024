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
The team narrowed its efforts on the collection, transformation, analysis and visualization of daily, county-level data (where available) for the five-year period between 2018 - 2022, focusing on the relationship between extreme events and the following:

__FEMA Datasets__ (extracted via APIs)
* [Disaster Declaration Summaries for State and Counties (1953 to 2023)](https://www.fema.gov/data-visualization/disaster-declarations-states-and-counties)
* [Public Assistance Funded Projects (1998 - 2023)](https://www.fema.gov/openfema-data-page/public-assistance-funded-projects-details-v1)

__Nationa CDC Datasets__ (ingested datasets downlated from CDC data library)
* [National Outbreak Reporting (2010 to 2022)](https://wonder.cdc.gov/nndss/nndss_weekly_tables_menu.asp)
* [Mortality Data for Public Use (2018 to 2023)](https://www.cdc.gov/nchs/nvss/mortality_public_use_data.htm)

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
* Maggie Rosen | [GitHub_@maggierosen](https://github.com/maggierosen/)
* Michael Szumski | [GitHub @mikeszumski](https://github.com/mikeszumski/)

## Other Acknowledgments
* Project instruction and requirements provided by [The Artificial Intelligence Boot Camp at UNC Charlotte](https://bootcamp.charlotte.edu/artificial-intelligence/)

