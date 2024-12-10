# Assignment B4

## Overview
This project contains two exercises in Part A of  STAT 545B Assignment 4:
1. **Exercise 1**: Analyzing word frequency in a book (specifically, a Jane Austen book) and visualizing the most common words after removing stopwords.
2. **Exercise 3**: Analyzing substance use data and building a linear regression model to predict abstinence days based on the number of treatment procedures for different substance use subgroups.

---

### Exercise 1: Word Frequency Analysis

#### Overview
In Exercise 1, we worked with a text from a Jane Austen novel (accessible via the `janeaustenr` R package) and analyzed the frequency of words in the book, excluding common stopwords such as “the”, “a”, and “of”. The objective was to generate a plot visualizing the most common words in the book, after removing these stopwords.

- The chosen book was "Pride and Prejudice", found in https://cran.r-project.org/web/packages/janeaustenr/janeaustenr.pdf 

We used the `tidytext` package to unnest the text into individual words and removed stopwords from the built-in `stop_words` dataset. The frequency of each word was then counted and sorted in descending order to highlight the most frequent words remaining after stopword removal.

---

### Exercise 3: Substance Use Data Analysis and Linear Regression

#### Overview
Exercise 3 involved analyzing a dataset related to substance use treatment and constructing a linear regression model to predict the number of abstinent days at 6 months (`ada_6`) based on the number of treatment procedures (`nproc`). This exercise also involved grouping the data by substance use subgroups to assess how treatment effectiveness varies across these subgroups.

#### Data
The dataset used in Exercise 3, named `sud`, contains information about individuals undergoing substance use disorder treatment from https://cran.r-project.org/web/packages/OVtool/vignettes/OVtool.html.
Key variables include:
- `ada_6`: The outcome variable, representing the number of abstinent days at 6 months.
- `nproc`: The number of treatment procedures delivered to each client.
- `subsgrps_n`: A categorical variable indicating the substance use subgroup (e.g., alcohol, opioids, etc.).

#### Methodology
For each substance use subgroup, we built linear regression models where the number of treatment procedures (`nproc`) was used to predict the number of abstinent days (`ada_6`). The models were fitted separately for each subgroup to assess how the treatment procedures were related to abstinence.


## Repository contents: 
- `STAT 545B Assignment B4 Part A - Andrea Wong Koo.Rmd`: contains both Exercise 1 and 3.
- `STAT 545B Assignment B4 Part A - Andrea Wong Koo.md`: contains the markdown version of the .Rmd file
- proj files

## Repository usage: 
To use this repository, you can either open the markdown file (.md), or the R markdown file (.Rmd) on R studio. 

