# Chicago_Education_Analyses

## Background

Suppose a local officer in charge of education who wants to improve college enrollment rates for schools in the Chicago region asks, which factors are actually correlated with college enrollment rates? Commonsense tells us that, better high schools of course have higher college enrollment rate; family and the community environment also play a big role, etc. We are interested in finding concrete metrics that quantify these influences and more importantly, in analysing how exactly are the metrics correlated to the college enrollment rate. For this purpose, we have gathered proper datasets from the official [Chicago Data Portal](https://data.cityofchicago.org/) and extracted the relevant information into a new dataset `CHICAGO_RESULTS`. The variables in `CHICAGO_RESULTS` are summarized in the `code.txt` file. After profound analyses of these data, we aim at proposing a few actionable suggestions for the officer.

## Highlights

        - Data exploration and visualization with ggplot2
        - Wilcoxon sum of rank test on distribution among groups
        - Linear regression with various model selection methods
        - Cross Validation for model and parameter selection
        - PCA and the LASSO for high dimension problem
