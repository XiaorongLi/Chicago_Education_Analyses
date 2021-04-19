# Chicago_Education_Analyses

## Background

Suppose a local officer in charge of education who wants to improve college enrollment rates for schools in the Chicago region asks, which factors are actually correlated with college enrollment rates? Commonsense tells us that, better high schools of course have higher college enrollment rate; family and the community environment also play a big role, etc. We are interested in finding concrete metrics that quantify these influences and more importantly, in analysing how exactly are the metrics correlated to the college enrollment rate. For this purpose, we have gathered proper datasets from the official [Chicago Data Portal](https://data.cityofchicago.org/) and extracted the relevant information into a new table `CHICAGO_RESULTS`. The variables in `CHICAGO_RESULTS` are summarized in the `code.txt` file. After profound analyses of these data, we aim at proposing a few actionable suggestions for the officer.

## Highlights

- Data exploration and visualization with ggplot2
- Wilcoxon sum of rank test on distribution among groups
- Linear regression with various model selection methods
- Cross Validation for model and parameter selection
- Missing value imputation

## Files

- `ChicagoCensusData.csv`  - Raw socioeconomic data from the Chicago Data Portal
- `ChicagoCrimeData.csv` - Raw crime data from the Chicago Data Portal
- `ChicagoPublicSchools.csv` - Raw educational data from the Chicago Data Portal
- `CHICAGO_RESULTS.csv` - Cleaned and joined data based on the data above (also stored on [IBM Db2 cloud](https://cloud.ibm.com/))
- `code.txt` - List of variable names used in the analyses
- `Chicago_Edu_Analyses.Rmd` R markdown file where all the analyses are performed.
