# College Distance Modeling

This project attempts to analyze and predict test scores for students against various social and economic factors

*Note: The easiest way to see the results of the project is to navigate [here](https://nbalepur.github.io/College-Distance-Modeling)*

## Data Tools

### Dataset

Our dataset is the CollegeDistance dataset which can be found [here](https://rdrr.io/cran/AER/man/CollegeDistance.html)

This dataset has a total of 4739 observations of 15 variables (14 predictors and 1 response). The said variables are:

- `gender`: a factor indicating gender
- `ethnicity`: factor indicating ethnicity (African-American, Hispanic or other)
- `score`: base year composite test score
- `fcollege`: factor. Is the father a college graduate?
- `mcollege`: factor. Is the mother a college graduate?
- `home`: factor. Does the family own their home?
- `urban`: factor. Is the school in an urban area?
- `unemp`: country unemployment rate in 1980
- `wage`: state hourly wage in manufacturing in 1980
- `distance`: distance from 4-year college (in 10 miles)
- `tuition`: average state 4-year college tuition (in 1000 USD)
- `education`: number of years of education
- `income`: factor. Is the family income above 25,000 USD per year?
- `region`: factor indicating region (West or other)

Our project attempts to predict `score` from a combination of the other varaibles

### Programming Languages

This project was created in R with a variety of libraries:

- `readr`
- `knitr`
- `faraway`
- `lmtest`
- `zoo`
- `ggplot2`
- `reshape2`
- `rsq`

## Getting Started

To get this project running on your machine, follow the steps below

### Viewing the Output

The simplest way to view the project is to go to [this link](https://nbalepur.github.io/College-Distance-Modeling), where you will be able to see the results of our project

Additionally, you can download the file `final-data-project.html` file and open it with your prefered browser

### Opening the Code

This project was created in R, so I recommend [R Studio](https://rstudio.com/) as the IDE to run the application

After installing R Studio, navigate to your preferred terminal and type the following command:

```
git clone https://github.com/nbalepur/College-Distance-Modeling.git
```

You will then see the following files:

- `CollegeDistance.csv`: The dataset used in this project
- `final-data-project.Rmd`: Contains the R Code for computations and calculations
- `final-data-project.html`: The HTML output of the project

## Authors

- Nishant Balepur
- Allison Zhang
- Kobe Dela Cruz

## Acknowledgements

This project was created as a final project for [STAT 420](http://daviddalpiaz.github.io/appliedstats/)
