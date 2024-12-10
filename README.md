# Assignment B4 Part A: Word Counts & Substance Use Data Analysis

## Overview
This project contains two exercises from Part A of STAT 545B Assignment 4:
1. **Exercise 1**: Word frequency analysis of a Jane Austen book, excluding stopwords.
2. **Exercise 3**: Substance use data analysis and linear regression to predict abstinent days based on treatment procedures.

---

### Exercise 1: Word Frequency Analysis
We analyzed a Jane Austen novel (specifically *Pride and Prejudice*) from the `janeaustenr` R package, visualizing the most common words after removing stopwords using the `tidytext` package. The text was tokenized, stopwords were filtered out, and word frequencies were calculated and sorted.

- Book Source: [Pride and Prejudice from `janeaustenr`](https://cran.r-project.org/web/packages/janeaustenr/janeaustenr.pdf)

---

### Exercise 3: Substance Use Data Analysis & Linear Regression
Using the `sud` dataset, we built linear regression models to predict the number of abstinent days (`ada_6`) based on treatment procedures (`nproc`). The analysis was performed for different substance use subgroups.

- Data Source: [OVtool Package](https://cran.r-project.org/web/packages/OVtool/vignettes/OVtool.html)
- Key Variables:
  - `ada_6`: Abstinent days at 6 months
  - `nproc`: Number of treatment procedures
  - `subsgrps_n`: Substance use subgroup (e.g., alcohol, opioids)

## Repository Contents
- `STAT 545B Assignment B4 Part A - Andrea Wong Koo.Rmd`: R markdown file containing both exercises.
- `STAT-545B-Assignment-B4-Part-A---Andrea-Wong-Koo.md`: Markdown version of the Rmd file.
- `STAT-545B-Assignment-B4-Part-A---Andrea-Wong-Koo_files`: Folder with figures generated.

## Repository Usage
Open either the `.md` or `.Rmd` file in RStudio to view or execute the analysis.
