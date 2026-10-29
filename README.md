# Margaux Reynolds

### Data science, thoughtful analysis, and useful products

I'm a fourth-year B.S. in Data Science student at the University of Virginia, graduating in May 2027. I'm interested in analytics, data engineering, and designing AI products and services.

My projects explore how data is organized, how models behave, and how to communicate results clearly.

## Selected projects

### [Beyond the Top 10: Movie Recommendation Bias](https://github.com/margauxreynolds/ds4320-project1-movielens)

**Individual course project · Python · SQL · DuckDB · Parquet · Surprise · Matplotlib**

Can a small change to a recommendation ranking give lesser-rated movies more exposure?

I organized MovieLens data into six Parquet tables, analyzed rating distributions with SQL, and built an SVD recommendation model. In the saved experiment for 500 users, a scoring adjustment increased lesser-rated movies' share of top-10 recommendation slots from **35.3% to 75.9%**.

**Takeaway:** Ranking choices can substantially change what gets shown. This experiment measures exposure; it does not establish improved user satisfaction or recommendation relevance.

[Read the project](https://github.com/margauxreynolds/ds4320-project1-movielens) · [Explore the analysis](https://github.com/margauxreynolds/ds4320-project1-movielens/blob/main/pipeline/pipeline.ipynb)

### [Credit Card Fraud Detection](https://github.com/margauxreynolds/ds4320-project-2)

**Course project · Python · MongoDB · pandas · scikit-learn · Matplotlib · seaborn**

What does a model miss when accuracy looks reassuring but fraud is rare?

This project uses MongoDB and class-weighted logistic regression to analyze 284,807 transactions. The saved test results show **91.8% recall and 6.1% precision**: the model identified 90 of 98 fraud cases, but also flagged 1,386 legitimate transactions.

**Takeaway:** Catching more fraud is only part of the problem. False positives create a review burden, so a useful evaluation needs to consider both missed fraud and unnecessary alerts.

[Read the project](https://github.com/margauxreynolds/ds4320-project-2) · [Explore the analysis and visualizations](https://github.com/margauxreynolds/ds4320-project-2/blob/main/pipeline/pipeline.ipynb)

## Tools used in these projects

- **Data preparation and storage:** Python, SQL, pandas, DuckDB, Parquet, MongoDB
- **Modeling and evaluation:** scikit-learn, Surprise, collaborative filtering, logistic regression
- **Communication:** Jupyter notebooks, Matplotlib, seaborn, written project explanations

## About this portfolio

These selected projects are the starting point for exploring my work. My other repositories include coursework and programming exercises.

Reported results come from the saved project notebooks. Each project should be read alongside its methods and limitations.
