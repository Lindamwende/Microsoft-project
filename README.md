# Microsoft-project
# MICROSOFT FILMS PROJECT

## 1.BUSINESS UNDERSTANDING

### 1.1. UNDERSTANDING THE PROBLEM

Microsoft is trying to come up with a new movie studio. The task is to explore different
types of films that are currently doing well at the box office. This is achieved by loading data
from a folder containing different datasets to work on. The findings are supposed to give
an idea of what actions Microsoft can take in order to start creating original video content.
Basically this is achieved by answering the following:
1. What genres are currently doing best in the movie world?
2. Averagely how much is the production budget and its return investment as
domestic gross to see how best the movies will fair locally before international
release.
3. The competition amongst the top studios in terms of their return investments.
#### PROBLEM STATEMENT

Following the cleaned datasets, come up with decisions Microsoft can take to create a
new movie studio.
# 2. DATA UNDERSTANDING

## 2.1. DATA COLLECTION

The data was collected from Box Office Mojo [https://www.boxofficemojo.com/] ,
TheMovieDB [https://www.themoviedb.org/] and The
Numbers[https://www.the-numbers.com/]. The procedure that followed was to get to know
what the datasets contained in their respective columns.
## 2.2. DATA DESCRIPTION

The first dataset contained 3387 rows and 5 columns and a number of missing values in
the studio, domestic_gross and foreign_gross column.
The MovieDB dataset contained 5782 rows and 6 columns with no missing values.
The Numbers dataset contained 1520 rows and 12 columns.
After describing the data, cleaning the data is what followed next.
# 2.3. DATA CLEANING

This was done to ensure the Validity, Accuracy, Completeness, Consistency and Uniformity
of the Data.
This was done by dropping rows that were not necessarily needed to answer the questions.
Next, checking if there were any outliers and dealing with them. Checking for missing
values too and finding out there were none helped the data cleaning process be more
easier.
Duplicated values were none in the first two datasets but the ones in the third dataset were
of importance to be able to know the most common genres.
New variables were created for the new columns that were merged to be able to get
adequate information to answer the questions.
# 3. DATA ANALYSIS

## 3.1. EXPLORATORY DATA ANALYSIS

## 3.1.1 UNIVARIATE DATA ANALYSIS

The category of interest is the Top 5 Genres. This being the Drama|Mystery and Suspense,
Drama, Comedy|Drama, Comedy Art House and International|Drama.
This category of interest accounts for more than 2000 rows of data but on further filtering
we come up with the popular produced genre films. The top 5 genres basically gives us the
answer to the third question.
## 3.1.2. BIVARIATE DATA ANALYSIS

According to the information in the production budget and domestic gross visualization, we
can see a positive correlation and the graphs are skewed positively.
From my analysis is not much to say concerning univariate and bivariate EDA.
# 4. RECOMMENDATIONS

1. I would suggest that Microsoft works on producing Drama related genres as they
are the ones that have been selling out more together with comedy films to place
them on the movies market.
2. Planing to use their production budget wisely to produce films and seeing how their
domestic gross returns would be in relation to their budget before releasing the
films internationally.
3. Watching out how various studios garner their profits with the type of films they
produce to be able to know their competition.
