
# Steam Games Data Analysis Project

## Overview

This project consists of a complete data analysis and machine learning pipeline applied to a dataset of games available on Steam. The work follows a **linear and structured process**, starting from data cleaning, moving through exploratory data analysis (EDA), and finishing with supervised learning experiments using Naive Bayes classifiers.

The goal of the project is **to understand patterns in game ratings and success**, analyze the influence of attributes such as genres, engines, developers, and franchises, and evaluate how well these features can be used to predict outcomes using probabilistic models.

---

## Project Structure and Linearity

The notebooks are organized to reflect a logical data science workflow. Each step depends on the results of the previous one.

### 1. Data Cleaning

**Notebook:** `Cleaning dataset`

* Initial inspection of the raw dataset
* Handling missing values
* Standardization of text fields (genres, developers, engines, etc.)
* Preparation of clean and consistent data for analysis

This step ensures data quality and prevents biases or errors in later stages.

---

### 2. Exploratory Data Analysis (EDA)

EDA is divided into thematic notebooks, each focusing on a specific aspect of the dataset.

#### 2.1 Rating Analysis

**Notebook:** `EDA Rating`

* Distribution of game ratings
* Central tendency and dispersion analysis
* Identification of skewness and general behavior of ratings

#### 2.2 Games and Engines

**Notebook:** `EDA Game and Engines`

* Frequency of game engines
* Relationship between engines and ratings
* Comparison between commonly used engines

#### 2.3 Developers and Publishers

**Notebook:** `EDA Developers`

* Analysis of top developers and publishers
* Rating behavior across different companies
* Concentration of highly rated games

#### 2.4 Game Franchises

**Notebook:** `EDA Game Franchises`

* Identification of recurring franchises
* Rating consistency within franchises
* Comparison between standalone games and franchise titles

EDA provides insights that guide feature selection and modeling decisions.

---

### 3. Machine Learning Experiments

The modeling phase focuses on probabilistic classification using Naive Bayes.

#### 3.1 Naive Bayes Baseline

**Notebook:** `Naive Bayes`

* Definition of the target variable
* Feature encoding and preprocessing
* Baseline Naive Bayes classifier
* Evaluation using accuracy and confusion matrices

#### 3.2 Genre-Based Classification

**Notebook:** `Naive Bayes for Genres`

* Focus on genre-related features
* Analysis of how genres impact prediction performance
* Comparison with baseline results

#### 3.3 Extended Experiments

**Notebook:** `Naive Bayes and Experiments`

* Feature combinations (genres, developers, engines)
* Performance comparison across experiments
* Discussion of model limitations and behavior

---

### 4. Final Analysis

**Notebook:** `Final Length`

* Consolidation of results
* Comparison between exploratory findings and model performance
* Final interpretation of the analysis pipeline

---

## Tools and Technologies Used

* **Python**
* **Google Colab / Jupyter Notebooks**
* **Pandas** – data manipulation and cleaning
* **NumPy** – numerical operations
* **Matplotlib & Seaborn** – data visualization
* **Scikit-learn** – machine learning models and evaluation

---

## Conclusions

* Data cleaning and standardization are critical for consistent analysis and modeling.
* Exploratory Data Analysis reveals clear patterns in ratings related to genres, engines, developers, and franchises.
* Naive Bayes provides a simple and interpretable baseline for classification tasks.
* Model performance is highly dependent on feature representation and data balance.
* The project demonstrates a complete and coherent data science workflow, from raw data to predictive modeling.

---

## Final Notes

This project emphasizes **methodology and reasoning**, showing how structured analysis and incremental experimentation lead to meaningful insights, even when using relatively simple machine learning models.


@antinomico @AndreLimaJordao @JoaoHenriqueMG @PeterIgnatious
