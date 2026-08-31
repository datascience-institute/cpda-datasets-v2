# CPDA Datasets (v2)

Practice datasets for the DSI Certified Professional Data Analyst (CPDA) programme, organised one folder per lesson.

This is a v2 restructure of the original [cpda-datasets](https://github.com/datascience-institute/cpda-datasets) repository: the same datasets are now grouped per lesson (matching the current lesson folder names) rather than per unit, so each lesson's practice materials can link directly to only the file(s) it uses.

Currently covers Part 1 (Data Analytics Foundation), Units 1-4. Other Parts may be added later.

## Structure

```
Part-1-Data-Analytics-Foundation/
  Unit-<N>-<Unit-Title>/
    L<N>-<Lesson-Title>/
      datasets/
        <dataset files used by that lesson's practice questions>
```

## Using a dataset directly (e.g. in Google Colab)

```python
import pandas as pd
df = pd.read_csv("<raw file URL from the lesson>")
```

## Lessons and datasets

### Unit 1 Python for Data Analysis

- **L1 Python Environment and First Programs** — `python_installation_survey.csv`
- **L3 Libraries and pandas Data Structures** — `student_profiles.csv`
- **L4 Numeric and String Functions** — `numeric_operations.csv`
- **L5 Control Flow - Conditionals and Loops** — `student_loops.csv`
- **L6 Files, Directories, Dates and Times** — `filesystem_operations.csv`

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
- **L3 Comparing Means with t-tests** — `INDEPENDENT SAMPLES t TEST.csv`, `ONE SAMPLE t TEST.csv`, `PAIRED t TEST.csv`
- **L4 Analysis of Variance** — `One way anova.csv`, `Two way anova.csv`
- **L5 Non-Parametric Tests** — `Kruskal Wallis Test.csv`, `Mann Whitney test.csv`, `Wilcoxon Signed Rank test for paired data.csv`
- **L6 Choosing the Right Test and Categorical Association** — `Correlation test.csv`, `chi square test of association.csv`
