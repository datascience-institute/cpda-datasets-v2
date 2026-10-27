# CPDA Datasets (v2)

Practice datasets for the DSI Certified Professional Data Analyst (CPDA) programme, organised one folder per lesson.

This is a v2 restructure of the original [cpda-datasets](https://github.com/datascience-institute/cpda-datasets) repository: the same datasets are now grouped per lesson (matching the current lesson folder names) rather than per unit, so each lesson's practice materials can link directly to only the file(s) it uses.

Covers Parts 1-4. Two Part 4 lessons carry no dataset (L3 Overfitting, Underfitting and the Bias-Variance Trade-off, and L4 Generalised Linear Modelling), as does Part 1 Unit 1 L2 Core Data Types and Structures; these are taught without a data file.

## Structure

```
Part-<N>-<Part-Title>/
  Unit-<N>-<Unit-Title>/
    L<N>-<Lesson-Title>/
      datasets/
        <dataset files used by that lesson's practice questions>
  Case-Studies/
    Case-Study-<Title>/
      <dataset files used by that case study>
      Case-Study-<Title>.zip
```

## Using a dataset directly (e.g. in Google Colab)

```python
import pandas as pd
df = pd.read_csv("<raw file URL from the lesson>")
```

## Lessons and datasets

## Part 1 Data Analytics Foundation

### Unit 1 Python for Data Analysis

- **L1 Python Environment and First Programs** — `python_installation_survey.csv`
- **L3 Libraries and pandas Data Structures** — `student_profiles.csv`
- **L4 Numeric and String Functions** — `numeric_operations.csv`
- **L5 Control Flow Conditionals and Loops** — `student_loops.csv`
- **L6 Files Directories Dates and Times** — `filesystem_operations.csv`

### Unit 2 Data Management

- **L1 Importing Data** — `east.csv`, `north.csv`, `retail_transactions.csv`, `south.csv`, `west.csv`
- **L2 Checking Data Features and Modifying Data** — `customer_churn.csv`
- **L3 Creating Subsets and Sorting Data** — `consumerpreference.csv`
- **L4 Merging and Aggregating** — `basic_salary - 1.csv`, `basic_salary - 2.csv`, `basic_salary.csv`, `bonus_data.csv`
- **L5 Handling Missing Values** — `basic_salary.csv`, `consumerpreference.csv`
- **L6 Building an ETL Workflow** — `retail_transactions.csv`

### Unit 3 Descriptive Statistics

- **L1 Descriptive Statistics in Python** — `Retail_Data.csv`
- **L2 Beyond Mean and Variance** — `Retail_Data.csv`
- **L3 Bivariate Relationships** — `Job_Proficiency.csv`
- **L4 Automated EDA Libraries** — `Retail_Data.csv`
- **L5 Sampling Methods for Research** — `survey_respondents.csv`

### Unit 4 Inferential Statistics

- **L1 Foundations of Statistical Inference** — `Normality Testing Data.csv`
- **L2 Checking Assumptions** — `F test for 2 variances.csv`, `Normality Testing Data.csv`
- **L3 Comparing Means with t tests** — `INDEPENDENT SAMPLES t TEST.csv`, `ONE SAMPLE t TEST.csv`, `PAIRED t TEST.csv`
- **L4 Analysis of Variance** — `One way anova.csv`, `Two way anova.csv`
- **L5 Non Parametric Tests** — `Kruskal Wallis Test.csv`, `Mann Whitney test.csv`, `Wilcoxon Signed Rank test for paired data.csv`
- **L6 Choosing the Right Test and Categorical Association** — `Correlation test.csv`, `chi square test of association.csv`

## Part 2 Data Visualisation

### Unit 1 Introduction to Data Visualisation

- **L1 Why Visualisation Matters and Choosing the Right Chart** — `monthly_sales.csv`
- **L2 Design Principles for Clarity and Credibility** — `company_sales.csv`
- **L3 Avoiding Misleading and Low Quality Visuals** — `visualization_survey.csv`
- **L4 Data Storytelling and Communicating Insight** — `appointment_cancellations.csv`

### Unit 2 Data Visualisation Using Python

- **L1 Categorical and Composition Charts** — `telecom_profile.csv`
- **L2 Distribution Plots** — `telecom_usage.csv`
- **L3 Visualising Relationships** — `employee_proficiency.csv`
- **L4 Chart Ready Summaries and Formatting for Communication** — `telecom_usage.csv`

## Part 3 Data Reduction and Unsupervised Analytics

### Unit 1 Dimensionality Reduction

- **L1 What Is Dimensionality and Why It Matters** — `Athleticsdata.csv`
- **L2 Redundancy Correlation and Multicollinearity** — `Athleticsdata.csv`
- **L3 When and Why to Reduce** — `Town Insurance.csv`

### Unit 2 Principal Component Analysis

- **L1 PCA Concepts and When to Use It** — `Sporting Goods Sales Data.csv`
- **L2 Running PCA in Python Scaling Components and Explained Variance** — `Athleticsdata.csv`
- **L3 Interpreting Loadings and Scores** — `Athleticsdata.csv`

### Unit 3 Clustering and Segmentation

- **L1 Introduction to Clustering and Unsupervised Learning** — `RETAILERS DATA.csv`
- **L2 The K Means Algorithm and Preprocessing** — `RETAILERS DATA.csv`
- **L3 Choosing k and Interpreting Clusters** — `RETAILERS DATA.csv`
- **L4 Profiling and Acting on Segments and the Limits of K Means** — `Customer Segments.csv`

## Part 4 Predictive Modelling

### Unit 1 Predictive Modelling Basics

- **L1 Introduction to Predictive Modelling** — `customer_churn.csv`, `housing_loan_applicants.csv`
- **L2 Regression versus Classification** — `House Price Data.csv`, `customer_churn.csv`

### Unit 2 Linear Regression

- **L1 Introduction to Multiple Linear Regression** — `Performance Index.csv`
- **L2 Interpreting Regression Output** — `Performance Index new.csv`, `Performance Index.csv`
- **L3 Using Categorical Variables** — `RESTAURANT SALES DATA.csv`
- **L4 Regression Diagnostics I Multicollinearity** — `ridge regression data.csv`
- **L5 Regression Diagnostics II Residuals and Influence** — `Performance Index.csv`
- **L6 Principal Component Regression** — `pcrdata.csv`, `pcrdata_test.csv`
- **L7 Model Selection and Performance** — `Performance Index.csv`

### Unit 3 Classification Models

- **L1 Introduction to Binary Logistic Regression I** — `BANK LOAN.csv`
- **L2 Binary Logistic Regression II** — `BANK LOAN.csv`
- **L3 Checking Model Performance** — `BANK LOAN.csv`
- **L5 Multinomial Logistic Regression** — `High School Data.csv`
- **L6 Ordinal Logistic Regression** — `Brand Preference Study.csv`

### Unit 4 Model Validation

- **L1 Validating Regression Models** — `Motor_Claims.csv`
- **L2 Validating Classification Models** — `BANK LOAN.csv`

## Case study datasets

Each case study has its own folder holding the dataset files and one `.zip` of those files. Download the zip, unzip it, and place the case study notebook in the unzipped folder: the notebook reads each file by its name.

### Part 1 Data Analytics Foundation

- **Banking Customer Churn and Credit Scores** — `Bank Churn.csv` ([zip](Part-1-Data-Analytics-Foundation/Case-Studies/Case-Study-Banking-Customer-Churn-and-Credit-Scores/Case-Study-Banking-Customer-Churn-and-Credit-Scores.zip))
- **FMCG Business Analytics** — `CUST_PROFILE.csv`, `NPSDATA.csv`, `NSVDATA.csv` ([zip](Part-1-Data-Analytics-Foundation/Case-Studies/Case-Study-FMCG-Business-Analytics/Case-Study-FMCG-Business-Analytics.zip))
- **FMCG NPS Study** — `CUST_PROFILE.csv`, `NPSDATA.csv` ([zip](Part-1-Data-Analytics-Foundation/Case-Studies/Case-Study-FMCG-NPS-Study/Case-Study-FMCG-NPS-Study.zip))
- **HR Employee Engagement** — `EMPLOYEE ENGAGEMENT DATA.csv` ([zip](Part-1-Data-Analytics-Foundation/Case-Studies/Case-Study-HR-Employee-Engagement/Case-Study-HR-Employee-Engagement.zip))
- **Hospitality Hotel Bookings and Revenue** — `Hospitality_Data.csv` ([zip](Part-1-Data-Analytics-Foundation/Case-Studies/Case-Study-Hospitality-Hotel-Bookings-and-Revenue/Case-Study-Hospitality-Hotel-Bookings-and-Revenue.zip))
- **Pharma Pain Relief Trial** — `VAS DATA.csv` ([zip](Part-1-Data-Analytics-Foundation/Case-Studies/Case-Study-Pharma-Pain-Relief-Trial/Case-Study-Pharma-Pain-Relief-Trial.zip))

### Part 2 Data Visualisation

- **Car Data Visualisation** — no dataset file: the notebook loads the built-in `mtcars` dataset with `pydataset`
- **Pizza Delivery Performance** — `pizzadata.csv` ([zip](Part-2-Data-Visualisation/Case-Studies/Case-Study-Pizza-Delivery-Performance/Case-Study-Pizza-Delivery-Performance.zip))

### Part 4 Predictive Modelling

- **Boston House Prices** — `Housing Prices.csv` ([zip](Part-4-Predictive-Modelling/Case-Studies/Case-Study-Boston-House-Prices/Case-Study-Boston-House-Prices.zip))
- **Food Delivery Time and Delay Prediction** — `pizzadata.csv` ([zip](Part-4-Predictive-Modelling/Case-Studies/Case-Study-Food-Delivery-Time-and-Delay-Prediction/Case-Study-Food-Delivery-Time-and-Delay-Prediction.zip))
- **ICU Mortality** — `ICU Mortality.csv` ([zip](Part-4-Predictive-Modelling/Case-Studies/Case-Study-ICU-Mortality/Case-Study-ICU-Mortality.zip))
- **Skin Clinic Campaign Response** — `Purchase Data 1.csv`, `Purchase Data 2.csv`, `Response Data.csv` ([zip](Part-4-Predictive-Modelling/Case-Studies/Case-Study-Skin-Clinic-Campaign-Response/Case-Study-Skin-Clinic-Campaign-Response.zip))
- **Used Car Selling Price** — `Vehicle Data.csv` ([zip](Part-4-Predictive-Modelling/Case-Studies/Case-Study-Used-Car-Selling-Price/Case-Study-Used-Car-Selling-Price.zip))
