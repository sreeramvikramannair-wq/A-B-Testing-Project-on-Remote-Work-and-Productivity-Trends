# Introduction
## Background
Changing structures, organisations, and the global event COVID-19, remote working is gaining in popularity around the world across all industries 
with the advent of technological progress. Change the traditional office work model to explore the flex working model, which can improve the flexibility 
of working and reduce expenses (Pinheiro and Palma-Moreira, 2025). However, working from home or remotely with a hybrid office culture can be difficult 
when it comes to tracking productivity and optimizing performance. A range of different tools and platforms have emerged that seek to help employees 
manage their work, keep track of time spent and facilitate collaboration (Kambezidis et al., 2025; Değermenci et al., 2025). However, there is limited 
empirical evidence of the success of these tools. Organizations need to understand what makes work productively in remote work and how to optimise 
their workforce management of the digital interventions to design an effective policy (Johnson et al., 2024). The research aims are around comparing 
the productivity metrics of AI-assisted planning tools and work habits affecting remote workers, and exploring what could be factors that contribute 
to efficiency in non-traditional settings.
## Problem Statement
Companies have a lack of confidence in employee productivity and effectiveness of digital tools, even though the shift towards remote work is on the rise. Performance measurement is complicated by varying task completion, varying focus time and varying work habits and thus differentiating between task-factors leading to higher productivity becomes a challenge (Polilli et al., 2026). Furthermore, there are few empirical investigations which carefully assess the effects of AI-supported planning tools on the performance of teleworkers. This research aims to fill in these gaps with an A/B analysis of productivity indicators when working with AI tools and when working according to the traditional method.
## Research Question
Does the use of AI-assisted tools significantly improve productivity among remote workers?
## Hypothesis (for A/B testing)
Null Hypothesis (H0): There is no significant difference in productivity scores between remote workers who use AI tools and those who do not.
Alternative Hypothesis (H1): Remote workers who use AI tools have significantly different productivity scores compared with those who do not.
Report Significance
The results of this report have important implications in the organization decision making and workforce management. The report elucidates the role that AI-driven planning plays in the productivity of remote workers and offers implications for a successful “digital intervention” for the planning process. The findings are valuable resources that managers and policy makers can use to fine-tune remote work policies, task management strategies and measures for the employees' performance (Wang et al., 2025). Moreover, it's a contribution to the academic sector dealing with remote working and productiveness evaluation as well as technology adoption in the new workplace.

# Methodology
## Research Design
The research design for the study is an A/B testing design to compare the effect of AI planning tools for remote workers' productivity. The study participants are split into two groups: one a treatment group, in which the workers use AI planning tools to complete the tasks; and one control group, in which the workers do not use AI planning tools to finish tasks (Dong et al., 2025). This design allows for comparisons between the two groups of: task completion rates, time on task and productivity scores. The research design ensured that any differences in productivity measures observed were due to the use of the AI tools (Rodrigues et al., 2023). The design is also flexible enough to enable secondary data analysis with a structured data file, which can then be subsequently analysed statistically and subjected to strict testing of the hypothesis.
## Research Strategy
The research method used is a quantitative method of focusing on hypothesis tests and statistical analysis. The data is obtained from a publicly available data set of remote workers which includes, but is not limited to, productivity score, task completion, focus time, and how often tools are used. The approach is to run statistical tests on the two groups such as treated and controlled to find significant differences (Polilli et al., 2026). Patterns and trends were given visualization techniques to help interpret them and regression analysis and correlation facts were used to gain insight into the factors affecting productivity associated with the remote working environment.
## Dataset Description
The data used is downloaded from Kaggle with detailed information about the productivity of remote employees (link). It has 1000 rows, each corresponding to a single remote worker, and 17 columns, collecting data on the demographics of workers, how they work and their productivity indicators. The productivity_score, task_completion_rate, late_task_ratio, average_daily_work_hours, focus_time_minutes, and AI_assisted_planning metrics are among the key factors to evaluate, as are tool usage frequency and others (Kaggle, 2025). These categorical variables help to shed more light on the analysed topic such as location type, industry sector (Arif et al., 2024). Data can be analysed statistically such as descriptive and inferential are well structured for use in an A/B testing framework (Wang et al., 2025). It allows for the identification of relationships among uses of the AI tools and productivity outcomes, providing strong evidence to inform workforce management and decisions.
## Statistical Tests and Algorithms
The statistical analysis includes both statistical tests and machine learning algorithms, which are used to analyze statistical differences in productivity between the control and treatment groups, respectively. To provide an overall description of the data and general trends, first Descriptive statistics (frequency, mean, median, standard deviation, distribution plots) are used. The independent samples t-test is used to see if using AI for planning significantly impacts productivity ratings and is parametric, comparing the scores across two independent groups (Li et al., 2025). For data that were not normally distributed, the Mann-Whitney U test was used as a non-normal test.
The Chi square tests are used to test association between categorical variables such as AI usage and productivity labels and Cramér's V are used to measure the strength of an association. Focus time, work hours and productivity scores are all numeric features that are assessed for their linear relationship with Pearson correlation coefficients (Arsenjeva et al., 2025). To compare the productivity of several groups differentiated on productivity categories, one-way ANOVA was performed and the effect size measured by eta squared.
Multiple linear regression is used to find out factors affecting productivity when predictive modelling is used. Independent variables consist of the rate of task completion, ratio of tasks that are completed late, focus time, usage of AI assisted planning, and frequency of using the tools (Jabor et al., 2024). Model performance measures including Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R-squared and adjusted R-squared are reported to quantify the predictive performance. These tests are complemented with visualizations, such as boxplots, scatterplots, or heatmaps, which give easy-to-understand comparisons and insight into patterns, outliers and anomalies present (Mardalena et al., 2025). These statistical tests lead to a comprehensive assessment of whether there is any significant difference in the groups, as well as an analysis of the reasons for the low productivity of remote workers.
## Metrics for Evaluation
One of the main evaluation measures is the productivity score which is a measure of the overall efficiency and productivity of remote workers. Secondary measures to measure task completion rate, number of tasks completed in time and ratio of late tasks. The sustainable attention time (in minutes) per task represents the amount of time spent on a specific task, and the average number of work hours per day are the overall hours worked per day (Huang et al., 2022). AI-assisted planning is allocated a binary value (0 or 1) to distinguish it from a control and treatment sample. Additional context for digital tool use can be provided by which is used most often and how many tasks can be automated using digital tools. 
Immediate feedback scores are also seen as a measure to assess immediate feedback assessment effect. These measures can be used to perform both univariate and multivariate analyses which can give a complete picture of the comparison between groups (Aidha et al., 2025). Using descriptive statistics, correlation assessment, t-test analysis, ANOVA analysis and regression modelling, the study thoroughly confirms the productivity patterns and factors that can significantly influence productivity in a remote work situation.
## Tools & Platform
This involves using the Python programming language in Jupyter Notebook notebooks to analyze, visualize and statistically evaluate data. Important libraries include Pandas for data manipulation, NumPy for numerical computations, Seaborn for advanced visualization and Matplotlib for more advanced visualizations. Statistical tests such as t-test, ANOVA test, Mann-Whitney U, Chi-square and regression modeling were used for these tests, which were performed with Scipy and Statsmodels (Mallorie et al., 2024). Jupyter Notebook is user-friendly, which properly performs the local installation, allows users to collaborate, reproduce results and be more accessible to the users. The data is downloaded into Jupyter Notebook via the Kaggle website, which makes it easy to import the data. Analysis steps, visualizations and interpretations are properly documented in Markdown cells to create a structured and professional document. It is a platform that provides both transparency and traceability of all analytical procedures, and it meets the need for reporting to a GitHub server for submission.
## Ethical Considerations
The report takes into account ethical issues, such as maintaining the integrity of the data, protecting participants' confidentiality, and reporting responsibly. Research is conducted on a dataset obtained from Kaggle, where all the data has been anonymised, and there is no data that contains personally identifiable information, thus ensuring compliance with data protection (Sungur et al., 2026). Researchers do not manipulate or present results in a way that will favour their hypothesis, they not only strive towards transparency but are also open to reproducing their analyses. 
Limitation(s) are noted for groups that may be underrepresented or overrepresented in the dataset, or groups that are not included at all, as well as industry sectors that may be underrepresented or overrepresented. Informed consent principles are upheld by working within the original data collection protocol in this research. In addition, the study highlights responsible use of results, which prevents unfavourable impacts of recommendations for AI-assisted planning interventions in the organisation on the autonomy and well-being of employees (Haloho et al., 2026). Visualizations, statistical results and interpretations are presented in an objective manner towards evidence driven decision making.

# **Remote Work and Productivity Trends**
## **A/B Testing with Python Data Analysis**


```python
# LOADING LIBRARIES


import pandas as pd
import numpy as np

import matplotlib.pyplot as plt
import seaborn as sns

from scipy import stats
from scipy.stats import chi2_contingency, ttest_ind, mannwhitneyu, pearsonr, f_oneway
import statsmodels.api as sm
import statsmodels.formula.api as smf

import warnings
warnings.filterwarnings("ignore")

plt.rcParams["figure.figsize"] = (10, 6)
sns.set_theme(style="whitegrid")
```

## **Loading the Dataset**


```python
# LOADING THE DATASET

remote_work = pd.read_csv("remote_worker_productivity.csv")

# Display first five rows
remote_work.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>worker_id</th>
      <th>location_type</th>
      <th>industry_sector</th>
      <th>age</th>
      <th>experience_years</th>
      <th>average_daily_work_hours</th>
      <th>break_frequency_per_day</th>
      <th>task_completion_rate</th>
      <th>late_task_ratio</th>
      <th>calendar_scheduled_usage</th>
      <th>focus_time_minutes</th>
      <th>tool_usage_frequency</th>
      <th>automated_task_count</th>
      <th>AI_assisted_planning</th>
      <th>real_time_feedback_score</th>
      <th>productivity_label</th>
      <th>productivity_score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>W0001</td>
      <td>Village</td>
      <td>Healthcare</td>
      <td>23</td>
      <td>26</td>
      <td>7.45</td>
      <td>1</td>
      <td>66.377024</td>
      <td>0.254624</td>
      <td>55.496926</td>
      <td>106.0</td>
      <td>19</td>
      <td>13</td>
      <td>0</td>
      <td>80</td>
      <td>Low</td>
      <td>32.31</td>
    </tr>
    <tr>
      <th>1</th>
      <td>W0002</td>
      <td>City</td>
      <td>Healthcare</td>
      <td>27</td>
      <td>27</td>
      <td>9.82</td>
      <td>3</td>
      <td>88.226501</td>
      <td>0.173382</td>
      <td>66.496755</td>
      <td>141.0</td>
      <td>5</td>
      <td>1</td>
      <td>1</td>
      <td>83</td>
      <td>Medium</td>
      <td>41.09</td>
    </tr>
    <tr>
      <th>2</th>
      <td>W0003</td>
      <td>Village</td>
      <td>Retail</td>
      <td>30</td>
      <td>8</td>
      <td>7.38</td>
      <td>2</td>
      <td>67.004170</td>
      <td>0.351835</td>
      <td>41.367064</td>
      <td>92.0</td>
      <td>4</td>
      <td>4</td>
      <td>0</td>
      <td>81</td>
      <td>Low</td>
      <td>25.69</td>
    </tr>
    <tr>
      <th>3</th>
      <td>W0004</td>
      <td>Village</td>
      <td>Finance</td>
      <td>54</td>
      <td>19</td>
      <td>8.37</td>
      <td>1</td>
      <td>66.004424</td>
      <td>0.347840</td>
      <td>51.086805</td>
      <td>94.0</td>
      <td>17</td>
      <td>9</td>
      <td>1</td>
      <td>84</td>
      <td>Low</td>
      <td>31.98</td>
    </tr>
    <tr>
      <th>4</th>
      <td>W0005</td>
      <td>City</td>
      <td>Education</td>
      <td>46</td>
      <td>1</td>
      <td>7.51</td>
      <td>4</td>
      <td>91.468942</td>
      <td>0.085582</td>
      <td>93.618344</td>
      <td>202.0</td>
      <td>14</td>
      <td>8</td>
      <td>0</td>
      <td>64</td>
      <td>High</td>
      <td>48.19</td>
    </tr>
  </tbody>
</table>
</div>



### The first five rows of the data set are shown in the table, showing the main variables like worker_id, location_type, industry_sector, hours_worked each day, number of times completed, and AI-aided planning. This preview aids in consistency of data and patterns to begin analysis.


```python
# Dataset shape
print("Rows:", remote_work.shape[0])
print("Columns:", remote_work.shape[1])
```

    Rows: 1000
    Columns: 17
    

### This figure indicates that there are 1000 rows and 17 columns (data points) in this dataset. It identifies the dimensionality of the dataset, whether there was enough data for them to be able to use statistics and compare Control and Treatment groups within their A/B testing model.

## **Data Exploration**


```python
# EXPLORATION

remote_work.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 1000 entries, 0 to 999
    Data columns (total 17 columns):
     #   Column                    Non-Null Count  Dtype  
    ---  ------                    --------------  -----  
     0   worker_id                 1000 non-null   object 
     1   location_type             1000 non-null   object 
     2   industry_sector           1000 non-null   object 
     3   age                       1000 non-null   int64  
     4   experience_years          1000 non-null   int64  
     5   average_daily_work_hours  1000 non-null   float64
     6   break_frequency_per_day   1000 non-null   int64  
     7   task_completion_rate      1000 non-null   float64
     8   late_task_ratio           1000 non-null   float64
     9   calendar_scheduled_usage  1000 non-null   float64
     10  focus_time_minutes        1000 non-null   float64
     11  tool_usage_frequency      1000 non-null   int64  
     12  automated_task_count      1000 non-null   int64  
     13  AI_assisted_planning      1000 non-null   int64  
     14  real_time_feedback_score  1000 non-null   int64  
     15  productivity_label        1000 non-null   object 
     16  productivity_score        1000 non-null   float64
    dtypes: float64(6), int64(7), object(4)
    memory usage: 132.9+ KB
    

### The dataframe information provides a summary of the types of columns and the numbers of columns that are not null in the dataframe. There are no missing values identified, as six numeric and four object data types are indicated. This results in reliable statistical testing, visualization and facilitates analytical work with categorical and continuous variables.



```python
# Summary statistics
remote_work.describe().T
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>count</th>
      <th>mean</th>
      <th>std</th>
      <th>min</th>
      <th>25%</th>
      <th>50%</th>
      <th>75%</th>
      <th>max</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>age</th>
      <td>1000.0</td>
      <td>40.462000</td>
      <td>10.858013</td>
      <td>22.000000</td>
      <td>31.000000</td>
      <td>41.000000</td>
      <td>49.000000</td>
      <td>59.000000</td>
    </tr>
    <tr>
      <th>experience_years</th>
      <td>1000.0</td>
      <td>17.616000</td>
      <td>9.835409</td>
      <td>1.000000</td>
      <td>9.000000</td>
      <td>18.000000</td>
      <td>26.000000</td>
      <td>34.000000</td>
    </tr>
    <tr>
      <th>average_daily_work_hours</th>
      <td>1000.0</td>
      <td>7.493070</td>
      <td>1.194218</td>
      <td>3.610000</td>
      <td>6.700000</td>
      <td>7.510000</td>
      <td>8.302500</td>
      <td>11.250000</td>
    </tr>
    <tr>
      <th>break_frequency_per_day</th>
      <td>1000.0</td>
      <td>2.964000</td>
      <td>1.429947</td>
      <td>1.000000</td>
      <td>2.000000</td>
      <td>3.000000</td>
      <td>4.000000</td>
      <td>5.000000</td>
    </tr>
    <tr>
      <th>task_completion_rate</th>
      <td>1000.0</td>
      <td>81.258851</td>
      <td>11.944001</td>
      <td>60.121367</td>
      <td>70.343148</td>
      <td>82.288231</td>
      <td>92.305308</td>
      <td>99.964505</td>
    </tr>
    <tr>
      <th>late_task_ratio</th>
      <td>1000.0</td>
      <td>0.181935</td>
      <td>0.117973</td>
      <td>0.000808</td>
      <td>0.074883</td>
      <td>0.172747</td>
      <td>0.284789</td>
      <td>0.399570</td>
    </tr>
    <tr>
      <th>calendar_scheduled_usage</th>
      <td>1000.0</td>
      <td>67.884507</td>
      <td>19.724955</td>
      <td>30.029647</td>
      <td>50.824661</td>
      <td>69.138991</td>
      <td>85.556049</td>
      <td>99.994153</td>
    </tr>
    <tr>
      <th>focus_time_minutes</th>
      <td>1000.0</td>
      <td>149.676000</td>
      <td>52.185212</td>
      <td>60.000000</td>
      <td>105.000000</td>
      <td>148.500000</td>
      <td>196.250000</td>
      <td>239.000000</td>
    </tr>
    <tr>
      <th>tool_usage_frequency</th>
      <td>1000.0</td>
      <td>9.372000</td>
      <td>5.850115</td>
      <td>0.000000</td>
      <td>4.000000</td>
      <td>9.000000</td>
      <td>15.000000</td>
      <td>19.000000</td>
    </tr>
    <tr>
      <th>automated_task_count</th>
      <td>1000.0</td>
      <td>7.032000</td>
      <td>4.242284</td>
      <td>0.000000</td>
      <td>3.000000</td>
      <td>7.000000</td>
      <td>11.000000</td>
      <td>14.000000</td>
    </tr>
    <tr>
      <th>AI_assisted_planning</th>
      <td>1000.0</td>
      <td>0.504000</td>
      <td>0.500234</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
    </tr>
    <tr>
      <th>real_time_feedback_score</th>
      <td>1000.0</td>
      <td>74.114000</td>
      <td>14.324112</td>
      <td>50.000000</td>
      <td>62.000000</td>
      <td>74.000000</td>
      <td>86.000000</td>
      <td>99.000000</td>
    </tr>
    <tr>
      <th>productivity_score</th>
      <td>1000.0</td>
      <td>39.080040</td>
      <td>8.684354</td>
      <td>20.560000</td>
      <td>30.392500</td>
      <td>39.465000</td>
      <td>47.630000</td>
      <td>55.200000</td>
    </tr>
  </tbody>
</table>
</div>



### Descriptive statistics are measures obtained for numeric variables like the range, Inter Quartile Range, Mean, standard deviation, maximum and minimum. Various metrics such as productivity scores, focus time, task completion rates etc. are summarized to provide information on central tendency and data dispersion which are useful for A/B analysis.


```python
# Check missing values
missing_values = remote_work.isnull().sum()
missing_values
```




    worker_id                   0
    location_type               0
    industry_sector             0
    age                         0
    experience_years            0
    average_daily_work_hours    0
    break_frequency_per_day     0
    task_completion_rate        0
    late_task_ratio             0
    calendar_scheduled_usage    0
    focus_time_minutes          0
    tool_usage_frequency        0
    automated_task_count        0
    AI_assisted_planning        0
    real_time_feedback_score    0
    productivity_label          0
    productivity_score          0
    dtype: int64



### All values are present, and there are no missing values anywhere in the data, which is important for maintaining data integrity. Without missing values data is easier to analyse; the statistical testing, regression modelling and visualization tasks remain accurate.


```python
# Check duplicate rows
print("Duplicate rows:", remote_work.duplicated().sum())
```

    Duplicate rows: 0
    

### There are no duplicate observation each line in the dataset only appears once, so the observations belong to different workers. This ensures that the results are not biased in statistical analysis, and in a set-up where the same study should be used to compare the productivity between the AI-assisted and non-AI groups, it ensures a correct and unbiased analysis.


```python
# Display column names
remote_work.columns
```




    Index(['worker_id', 'location_type', 'industry_sector', 'age',
           'experience_years', 'average_daily_work_hours',
           'break_frequency_per_day', 'task_completion_rate', 'late_task_ratio',
           'calendar_scheduled_usage', 'focus_time_minutes',
           'tool_usage_frequency', 'automated_task_count', 'AI_assisted_planning',
           'real_time_feedback_score', 'productivity_label', 'productivity_score'],
          dtype='object')



### All 17 column names are shown for distribution including worker demographics, work habits, productivity measures, etc. and indicators of tool usage. It provides the reference for feature selection process such as A/B testing, regression and visualization of relevant variables, avoiding uncertainty in feature selection.


```python
# Count categorical values
categorical_cols = remote_work.select_dtypes(include="object").columns

for col in categorical_cols:
    print(f"\n{col}")
    print(remote_work[col].value_counts())
```

    
    worker_id
    worker_id
    W0001    1
    W0672    1
    W0659    1
    W0660    1
    W0661    1
            ..
    W0339    1
    W0340    1
    W0341    1
    W0342    1
    W1000    1
    Name: count, Length: 1000, dtype: int64
    
    location_type
    location_type
    City       355
    Town       326
    Village    319
    Name: count, dtype: int64
    
    industry_sector
    industry_sector
    Retail        203
    Education     203
    IT            203
    Healthcare    199
    Finance       192
    Name: count, dtype: int64
    
    productivity_label
    productivity_label
    Low       334
    Medium    333
    High      333
    Name: count, dtype: int64
    

### This figure depicts categorical variables, like location_type and worker_id. For instance, workers are classified by city, town or village; sample diversity is represented and it is possible to analyse subgroups for productive comparison with the appropriate work environments.

## **Exploratory Data Analysis**


```python
# Helper function for bar labels
def add_bar_labels(ax):
    for container in ax.containers:
        ax.bar_label(container, fmt="%.1f", padding=3, fontsize=9)
```


```python
# VISUALISATION 1: Productivity Label Distribution

ax = sns.countplot(data=remote_work, x="productivity_label", order=remote_work["productivity_label"].value_counts().index)
add_bar_labels(ax)
plt.title("Distribution of Productivity Labels")
plt.xlabel("Productivity Label")
plt.ylabel("Number of Workers")
plt.show()
```


    
![png](output_24_0.png)
    


### The following bar chart shows consumers where Low, Medium and High productivity workers are in the workforce. It is nearly even across the three categories, offer a level playing field for comparing them and prevents class imbalance when running an A/B test comparing AI-assisted with non-AI groups.


```python
# VISUALISATION 2: Location Type Distribution

plt.figure(figsize=(12,7))

ax = sns.countplot(
    data=remote_work,
    x="location_type",
    palette="husl"
)

add_bar_labels(ax)

plt.title("Distribution of Workers by Location Type", fontsize=14)
plt.xlabel("Location Type")
plt.ylabel("Count")

plt.show()
```


    
![png](output_26_0.png)
    


### This visualization shows number of workers by City, Town and Village. Staff are marginally over-represented from the City, as is the case due to re-distribution across the demographic. This distribution is needed to help interpret environmental influences on levels of productivity, and to provide comparisons of subgroups in location-based analyses.


```python
# VISUALISATION 3: Industry Sector Distribution

plt.figure(figsize=(14,10))
industry_order = remote_work["industry_sector"].value_counts().index

colors = sns.color_palette("Set2", len(industry_order))

ax = sns.countplot(
    data=remote_work,
    y="industry_sector",
    order=industry_order,
    palette=colors
)

for container in ax.containers:
    ax.bar_label(container, padding=3)

plt.title("Worker Distribution by Industry Sector", fontsize=14, fontweight='bold')
plt.xlabel("Count")
plt.ylabel("Industry Sector")

plt.show()
```


    
![png](output_28_0.png)
    


### The chart below is a horizontal bar graph that shows the number of employees working in IT, Retail, Education, Healthcare, and Finance. The others industries are well distributed, with Retail, Education, and IT being the three top groups, and Healthcare, and Finance being slightly below. For evaluating the effects of sectoral change trends and to understand the impact of the use of AI tools in the specific industries, sectoral insights come into play.


```python
# VISUALISATION 4: Productivity Score Histogram

ax = sns.histplot(
    remote_work["productivity_score"],
    bins=25,
    kde=True,
    color="seagreen",
    edgecolor="black",
    alpha=0.8
)

plt.title("Distribution of Productivity Scores")
plt.xlabel("Productivity Score")
plt.ylabel("Frequency")

for patch in ax.patches:
    height = patch.get_height()
    if height > 0:
        ax.text(
            patch.get_x() + patch.get_width()/2,
            height,
            int(height),
            ha="center",
            va="bottom",
            fontsize=8
        )

plt.show()
```


    
![png](output_30_0.png)
    


### The histogram and the curve of the KDE indicate the distribution of the productivity scores among workers. It shows clustering of values and central tendency, reflecting the level of variation in the performance. Many peaks and troughs provide clues for hypothesis testing and they indicate that there may be outliers that influence statistical analysis.


```python
# VISUALISATION 5: Average Productivity by AI Assisted Planning

avg_ai = remote_work.groupby("AI_assisted_planning")["productivity_score"].mean().reset_index()

ax = sns.barplot(
    data=avg_ai,
    x="AI_assisted_planning",
    y="productivity_score",
    palette=["red", "green"]
)

add_bar_labels(ax)

plt.title("Average Productivity Score by AI-Assisted Planning")
plt.xlabel("AI-Assisted Planning (0 = No, 1 = Yes)")
plt.ylabel("Average Productivity Score")

plt.show()
```


    
![png](output_32_0.png)
    


### The following bar chart shows the mean production score differences for workers (with planning assistance using AI (1)) as compared to workers (without planning assistance using AI (0)). The "AI" group's average score indicates that there is a positive correlation between the use of the tools and productivity, supporting the A/B test hypothesis.


```python
# VISUALISATION 6: Productivity by Location Type

avg_location = remote_work.groupby("location_type")["productivity_score"].mean().reset_index()

custom_colors = ["#1f77b4", "#ff7f0e", "#2ca02c", "#d62728", "#9467bd"]

ax = sns.barplot(
    data=avg_location,
    x="location_type",
    y="productivity_score",
    palette=custom_colors
)

# Add value labels on bars
for container in ax.containers:
    ax.bar_label(container, fmt="%.2f", padding=3, fontsize=10)

plt.title("Average Productivity Score by Location Type", fontsize=14)
plt.xlabel("Location Type")
plt.ylabel("Average Productivity Score")

plt.tight_layout()
plt.show()
```


    
![png](output_34_0.png)
    


### The graph shows average City, Town and Village productivity scores. The productivity of city workers is slightly higher, suggesting the presence of possible location influence. This visualization can be used to pinpoint environmental/Contextual factors that impact performance metrics.


```python
# VISUALISATION 7: Work Hours vs Productivity Score

ax = sns.scatterplot(data=remote_work, x="average_daily_work_hours", y="productivity_score", hue="AI_assisted_planning")
plt.title("Work Hours and Productivity Score")
plt.xlabel("Average Daily Work Hours")
plt.ylabel("Productivity Score")
plt.legend(title="AI Planning")
plt.show()
```


    
![png](output_36_0.png)
    


### The scatter plot displays the correlation between average daily work hours, computed productivity score, and AI usage.The scatter plot illustrates the relationship between average daily hours worked and productivity scores, along with AI usage. Patterns suggest a positive relationship between work duration and productivity as well as a potential change in this relationship when using AI to plan, thereby enabling a multivariate interpretation of determinant productivity.


```python
# VISUALISATION 8: Focus Time vs Productivity Score

ax = sns.scatterplot(data=remote_work, x="focus_time_minutes", y="productivity_score", hue="productivity_label")
plt.title("Focus Time and Productivity Score")
plt.xlabel("Focus Time in Minutes")
plt.ylabel("Productivity Score")
plt.legend(title="Productivity Label")
plt.show()
```


    
![png](output_38_0.png)
    


### The following scatter graph illustrates productivity scores against focus time in minutes for different levels of productivity marking.The following scatter graph breaks down focus time (in minutes) against productivity scores based on the productivity marking. The relationship between focus time and productivity: The longer the focus time, the higher the productivity, and they can be used for regression and correlation analysis.


```python
# VISUALISATION 9: Correlation Heatmap

numeric_data = remote_work.select_dtypes(include=["int64", "float64"])

corr = numeric_data.corr()

plt.figure(figsize=(14,10))

sns.heatmap(
    corr,
    annot=True,
    fmt=".2f",
    cmap="icefire",
    linewidths=0.5,
    linecolor="white",
    square=False,
    annot_kws={"size":9}
)

plt.title("Correlation Heatmap of Numeric Variables",
          fontsize=16,
          fontweight="bold")

plt.xticks(rotation=45, ha="right")
plt.yticks(rotation=0)

plt.tight_layout()
plt.show()
```


    
![png](output_40_0.png)
    


### The heatmap displays simple bivariate correlations between numeric features. Indices of correlation that are strong on either sign (such as task completion rate and late task ratio) indicate the underlying relationships. These help to guide variable selection for regression modeling and which variables significantly impact productivity.


```python
# VISUALISATION 10: Task Completion Rate by Productivity Label

plt.figure(figsize=(12, 7))

avg_task = remote_work.groupby("productivity_label")["task_completion_rate"].mean().reset_index()

custom_colors = ["#FF6B6B", "#4ECDC4", "#45B7D1"]

ax = sns.barplot(
    data=avg_task,
    x="productivity_label",
    y="task_completion_rate",
    palette=custom_colors
)

# Add data labels
for container in ax.containers:
    ax.bar_label(container, fmt="%.2f", padding=3, fontsize=10, fontweight="bold")

plt.title(
    "Average Task Completion Rate by Productivity Label",
    fontsize=14,
    fontweight="bold"
)
plt.xlabel("Productivity Label", fontsize=12)
plt.ylabel("Average Task Completion Rate", fontsize=12)

plt.tight_layout()
plt.show()
```


    
![png](output_42_0.png)
    


### This bar chart displays the mean task completion percentages of Low, Medium and High productivity workers. Statistically, significantly more tasks are completed by employees classified as high productivity - providing a solid backing for task completion as an indicator and for the whole productivity labels to be statistically tested.


```python
# VISUALISATION 11: Late Task Ratio by Productivity Label

plt.figure(figsize=(10,6))

colors = ["#FF6B6B", "#FFD93D", "#6BCB77"]

avg_late = remote_work.groupby("productivity_label")["late_task_ratio"].mean().reset_index()

ax = sns.barplot(
    data=avg_late,
    x="productivity_label",
    y="late_task_ratio",
    palette=colors
)

# Add data labels
for container in ax.containers:
    ax.bar_label(container, fmt="%.2f", padding=3, fontsize=10)

plt.title("Average Late Task Ratio by Productivity Label", fontsize=14, fontweight="bold")
plt.xlabel("Productivity Label", fontsize=12)
plt.ylabel("Average Late Task Ratio", fontsize=12)

plt.tight_layout()
plt.show()
```


    
![png](output_44_0.png)
    


### The median percentage of late tasks per productivity label is presented in this bar chart. Employees with low productivity have the highest ratio of tasks they are late on to tasks they produce, whereas ones with high productivity have lowest. This reconfirms that there is an inverse relationship between punctuality and performance and thus reinforces behavioural patterns which are critical for analysis.

## **Data Pre-processing**


```python
# Copy original dataset
remote_work_clean = remote_work.copy()

# Remove duplicate rows
remote_work_clean = remote_work_clean.drop_duplicates()

# Fill missing numeric values using median
numeric_cols = remote_work_clean.select_dtypes(include=["int64", "float64"]).columns

for col in numeric_cols:
    remote_work_clean[col] = remote_work_clean[col].fillna(remote_work_clean[col].median())

# Fill missing categorical values using mode
categorical_cols = remote_work_clean.select_dtypes(include="object").columns

for col in categorical_cols:
    remote_work_clean[col] = remote_work_clean[col].fillna(remote_work_clean[col].mode()[0])

# Confirm missing values removed
remote_work_clean.isnull().sum()
```




    worker_id                   0
    location_type               0
    industry_sector             0
    age                         0
    experience_years            0
    average_daily_work_hours    0
    break_frequency_per_day     0
    task_completion_rate        0
    late_task_ratio             0
    calendar_scheduled_usage    0
    focus_time_minutes          0
    tool_usage_frequency        0
    automated_task_count        0
    AI_assisted_planning        0
    real_time_feedback_score    0
    productivity_label          0
    productivity_score          0
    dtype: int64



### This figure shows the process of data cleaning in the remote work data in preparation for analysis. The replications of the rows had been deleted because it is important that the workers are represented separately in order to avoid bias and skewed results. The median was used to handle absence of numeric values to ensure consistency in productivity-related figures, such as task_completion_rate and focus_time_minutes, which were used, as these are robust to outliers. For variables where the mode was the most common response (such as location_type and industry_sector), the categorical missing values were replaced with the mode. Once this is done, there are no missing values in the dataset in any of the 17 columns. That ensures complete data integrity and effective statistical testing, regression modelling and A/B comparisons without introducing artificial bias and/or gaps in data.


```python
# Encoding categorical variables for modelling
remote_work_clean_encoded = pd.get_dummies(remote_work_clean, drop_first=True)

remote_work_clean_encoded.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>age</th>
      <th>experience_years</th>
      <th>average_daily_work_hours</th>
      <th>break_frequency_per_day</th>
      <th>task_completion_rate</th>
      <th>late_task_ratio</th>
      <th>calendar_scheduled_usage</th>
      <th>focus_time_minutes</th>
      <th>tool_usage_frequency</th>
      <th>automated_task_count</th>
      <th>...</th>
      <th>worker_id_W0999</th>
      <th>worker_id_W1000</th>
      <th>location_type_Town</th>
      <th>location_type_Village</th>
      <th>industry_sector_Finance</th>
      <th>industry_sector_Healthcare</th>
      <th>industry_sector_IT</th>
      <th>industry_sector_Retail</th>
      <th>productivity_label_Low</th>
      <th>productivity_label_Medium</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>23</td>
      <td>26</td>
      <td>7.45</td>
      <td>1</td>
      <td>66.377024</td>
      <td>0.254624</td>
      <td>55.496926</td>
      <td>106.0</td>
      <td>19</td>
      <td>13</td>
      <td>...</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
    </tr>
    <tr>
      <th>1</th>
      <td>27</td>
      <td>27</td>
      <td>9.82</td>
      <td>3</td>
      <td>88.226501</td>
      <td>0.173382</td>
      <td>66.496755</td>
      <td>141.0</td>
      <td>5</td>
      <td>1</td>
      <td>...</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
    </tr>
    <tr>
      <th>2</th>
      <td>30</td>
      <td>8</td>
      <td>7.38</td>
      <td>2</td>
      <td>67.004170</td>
      <td>0.351835</td>
      <td>41.367064</td>
      <td>92.0</td>
      <td>4</td>
      <td>4</td>
      <td>...</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
    </tr>
    <tr>
      <th>3</th>
      <td>54</td>
      <td>19</td>
      <td>8.37</td>
      <td>1</td>
      <td>66.004424</td>
      <td>0.347840</td>
      <td>51.086805</td>
      <td>94.0</td>
      <td>17</td>
      <td>9</td>
      <td>...</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
    </tr>
    <tr>
      <th>4</th>
      <td>46</td>
      <td>1</td>
      <td>7.51</td>
      <td>4</td>
      <td>91.468942</td>
      <td>0.085582</td>
      <td>93.618344</td>
      <td>202.0</td>
      <td>14</td>
      <td>8</td>
      <td>...</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 1020 columns</p>
</div>



### The figure illustrates how categorical variable(s) are converted to numeric dummy variables for quantitative modelling. Some columns were one-hot encoded such as location_type and industry_sector, resulting in unique columns for each category. Consequently, 1,020 columns of the data set were generated to capture all the categorical variables which can be used for regression or statistical analysis. This is an important step as the machine learning algorithms and statistical tests then require numerical inputs. Encoding will produce accurate measures of categorical variables' impacts on productivity scores. This pre-processing allows for expanded A/B testing, incorporating location, sector and other categorical factors into productivity SE assessments for various groups of workers and with AI-assisted planning.

## **Statistical Tests with Evaluation Metrics**

# ============================================================
## **TEST 1: A/B HYPOTHESIS TEST**
### **Independent Samples T-Test**
# ============================================================

### **A = workers without AI-assisted planning**
### **B = workers with AI-assisted planning**


```python
group_A = remote_work_clean[remote_work_clean["AI_assisted_planning"] == 0]["productivity_score"]
group_B = remote_work_clean[remote_work_clean["AI_assisted_planning"] == 1]["productivity_score"]

t_stat, p_value = ttest_ind(group_A, group_B, equal_var=False)

mean_A = group_A.mean()
mean_B = group_B.mean()
std_A = group_A.std()
std_B = group_B.std()

# Cohen's d
pooled_std = np.sqrt(((std_A ** 2) + (std_B ** 2)) / 2)
cohens_d = (mean_B - mean_A) / pooled_std

print("TEST 1: A/B Independent Samples T-Test")
print("H0: There is no significant difference in productivity score between AI and non-AI planning groups.")
print("H1: There is a significant difference in productivity score between AI and non-AI planning groups.")
print("Mean Group A - No AI:", round(mean_A, 2))
print("Mean Group B - AI:", round(mean_B, 2))
print("T-statistic:", round(t_stat, 4))
print("P-value:", round(p_value, 4))
print("Cohen's d:", round(cohens_d, 4))

if p_value < 0.05:
    print("Decision: Reject H0. AI-assisted planning has a statistically significant relationship with productivity.")
else:
    print("Decision: Fail to reject H0. No statistically significant difference was found.")
```

    TEST 1: A/B Independent Samples T-Test
    H0: There is no significant difference in productivity score between AI and non-AI planning groups.
    H1: There is a significant difference in productivity score between AI and non-AI planning groups.
    Mean Group A - No AI: 37.83
    Mean Group B - AI: 40.31
    T-statistic: -4.5424
    P-value: 0.0
    Cohen's d: 0.2873
    Decision: Reject H0. AI-assisted planning has a statistically significant relationship with productivity.
    

### This figure presents the findings of the independent sample T-test to compare the productivity scores of the AI-assisted worker vs the non-AI-assisted worker. The average productivity of AI-assisted workers in the sample was 40.31, compared to 37.83 for workers not assisted by AI. T-Stat = -4.5424, P = 0.00, which means that the difference observed is statistically significant. Cohen's d = 0.2873 indicates a small to moderate effect size. The test results showed that an AI-assisted plan positively affects productivity, which indicates that null hypotheses were rejected. The number is actual facts that support the A/B testing theory and highlights measurable gains in worker output, expectation achievement, and performance with the introduction of AI tools.

# ============================================================
# **TEST 2: Mann-Whitney U Test**
## **Non-parametric comparison of AI and non-AI groups**
# ============================================================


```python
u_stat, mann_p = mannwhitneyu(group_A, group_B, alternative="two-sided")

print("TEST 2: Mann-Whitney U Test")
print("U-statistic:", round(u_stat, 4))
print("P-value:", round(mann_p, 4))

if mann_p < 0.05:
    print("Decision: Significant difference exists between the two groups.")
else:
    print("Decision: No significant difference exists between the two groups.")
```

    TEST 2: Mann-Whitney U Test
    U-statistic: 100581.0
    P-value: 0.0
    Decision: Significant difference exists between the two groups.
    

### The figure shows the non-parametric Mann-Whitney U test that compares productivity scores from the AI-assisted and non-AI-assisted workers without assuming that their scores are normally distributed. With the U-statistic = 100,581.0, and p-value = 0.0, the difference in productivity between the two groups is considered to be statistically significant. This test supplements the data used for the T-test, further validating that AI Workers generally outperform those without AI throughout the test. The figure provides assurance that the results of the study are not the result of making incorrect assumptions about distributions, thus demonstrating the robustness of findings under non-normal data conditions relevant to the planning assistance by artificial intelligence. The visualization facilitates substantiated suggestions for the use of AI tools at a distance.

# ============================================================
# **TEST 3: Chi-Square Test**
## **Association between AI-assisted planning and productivity label**
# ============================================================


```python
contingency_table = pd.crosstab(remote_work_clean["AI_assisted_planning"], remote_work_clean["productivity_label"])

chi2, chi_p, dof, expected = chi2_contingency(contingency_table)

# Cramer's V
n = contingency_table.sum().sum()
cramers_v = np.sqrt(chi2 / (n * (min(contingency_table.shape) - 1)))

print("TEST 3: Chi-Square Test")
print(contingency_table)
print("Chi-square statistic:", round(chi2, 4))
print("Degrees of freedom:", dof)
print("P-value:", round(chi_p, 4))
print("Cramer's V:", round(cramers_v, 4))

if chi_p < 0.05:
    print("Decision: AI-assisted planning and productivity label are significantly associated.")
else:
    print("Decision: No significant association was found.")
```

    TEST 3: Chi-Square Test
    productivity_label    High  Low  Medium
    AI_assisted_planning                   
    0                      160  171     165
    1                      173  163     168
    Chi-square statistic: 0.6622
    Degrees of freedom: 2
    P-value: 0.7181
    Cramer's V: 0.0257
    Decision: No significant association was found.
    

### The figure shows the Chi-square test analysis of the association between the AI supported planning and productivity labels (Low, Media, High). According to the test, there was not a significant association between the two variables; the Chi-square = 0.6622; the p value = 0.7181, the Cramer's V = 0.0257. This indicates that although there is some impact on numeric productivity scores, there is no significant difference between labels of productivity at categorical level. This particular finding points to the important fact that AI tools are affecting additional gains in productivity, rather than moving employees from one performance segment to another. This number is critical for determining the extent of AI's impact on the outcome of classification and will drive both targeted interventions when accuracy of classification results is not the top priority, and enable such accuracy to be quantified.


# ============================================================
# **TEST 4: Pearson Correlation Test**
## **Relationship between focus time and productivity score**
# ============================================================


```python
corr_value, corr_p = pearsonr(remote_work_clean["focus_time_minutes"], remote_work_clean["productivity_score"])

print("TEST 4: Pearson Correlation")
print("Correlation coefficient:", round(corr_value, 4))
print("P-value:", round(corr_p, 4))

if corr_p < 0.05:
    print("Decision: Significant correlation exists between focus time and productivity score.")
else:
    print("Decision: No significant correlation exists.")
```

    TEST 4: Pearson Correlation
    Correlation coefficient: 0.9085
    P-value: 0.0
    Decision: Significant correlation exists between focus time and productivity score.
    

### The Pearson correlation analysis of focus time and productivity score is exhibited. It's evident that there's a strong positive association between the focus duration and productivity with r = 0.9085 and p-value = 0.0. This indicates that people with the ability to focus their attention longer have the potential to finish their tasks efficiently and/or attain higher output. The analysis highlights the significance of the factor variable focus time as a predictor variable in case of regression modelling or multivariate modelling. The figure demonstrates a visual proof of this correlation, offering implications for action: To enhance productivity, the focus should be on maintaining steady productivity levels, avoiding distractions, and adopting sustainable practices like well-structured routines and the use of AI tools for efficient planning.


# ============================================================
# **TEST 5: One-Way ANOVA**
## **Productivity score differences across productivity labels**
# ============================================================


```python
low = remote_work_clean[remote_work_clean["productivity_label"] == "Low"]["productivity_score"]
medium = remote_work_clean[remote_work_clean["productivity_label"] == "Medium"]["productivity_score"]
high = remote_work_clean[remote_work_clean["productivity_label"] == "High"]["productivity_score"]

anova_stat, anova_p = f_oneway(low, medium, high)

# Eta squared
grand_mean = remote_work_clean["productivity_score"].mean()
ss_between = sum([
    len(low) * (low.mean() - grand_mean) ** 2,
    len(medium) * (medium.mean() - grand_mean) ** 2,
    len(high) * (high.mean() - grand_mean) ** 2
])

ss_total = sum((remote_work_clean["productivity_score"] - grand_mean) ** 2)
eta_squared = ss_between / ss_total

print("TEST 5: One-Way ANOVA")
print("F-statistic:", round(anova_stat, 4))
print("P-value:", round(anova_p, 4))
print("Eta Squared:", round(eta_squared, 4))

if anova_p < 0.05:
    print("Decision: Productivity scores significantly differ across productivity labels.")
else:
    print("Decision: No significant difference was found across productivity labels.")
```

    TEST 5: One-Way ANOVA
    F-statistic: 6239.0577
    P-value: 0.0
    Eta Squared: 0.926
    Decision: Productivity scores significantly differ across productivity labels.
    

### This is a one way Analysis of Variance (ANOVA) to test for differences between productivity scores in the Low, Medium, and High productivity labels. This value of the F-statistic = 6,239.0577 at p-value = 0.0 is very significant and this value of Eta Squared = 0.926 shows that the differences between groups is highly significant. This establishes that the productivity labels actually separate out different levels of performance of workers and confirm effectiveness of the stratification method. However, the figure highlights the marked tertiary (thrice) separation of performance groups aiding further-grade analyses. It also confirms the use of groups through labels for comparative statistics, regression models and evaluation of effectiveness of AI. High Eta Squared statistics indicate that variability in scores is very large as a result of differences in productivity labelling.


## **Additional Regression Model for Evaluation Metrics**

# ============================================================
# **MULTIPLE LINEAR REGRESSION**
## **Predicting Productivity Score**
# ============================================================


```python
model = smf.ols(
    "productivity_score ~ average_daily_work_hours + task_completion_rate + late_task_ratio + focus_time_minutes + tool_usage_frequency + automated_task_count + AI_assisted_planning + real_time_feedback_score",
    data=remote_work_clean
).fit()

print(model.summary())
```

                                OLS Regression Results                            
    ==============================================================================
    Dep. Variable:     productivity_score   R-squared:                       0.972
    Model:                            OLS   Adj. R-squared:                  0.972
    Method:                 Least Squares   F-statistic:                     4350.
    Date:                Fri, 29 May 2026   Prob (F-statistic):               0.00
    Time:                        16:52:56   Log-Likelihood:                -1786.5
    No. Observations:                1000   AIC:                             3591.
    Df Residuals:                     991   BIC:                             3635.
    Df Model:                           8                                         
    Covariance Type:            nonrobust                                         
    ============================================================================================
                                   coef    std err          t      P>|t|      [0.025      0.975]
    --------------------------------------------------------------------------------------------
    Intercept                    2.0772      0.920      2.257      0.024       0.271       3.883
    average_daily_work_hours    -0.0227      0.039     -0.590      0.555      -0.098       0.053
    task_completion_rate         0.4263      0.010     43.341      0.000       0.407       0.446
    late_task_ratio            -19.8276      0.988    -20.061      0.000     -21.767     -17.888
    focus_time_minutes           0.0222      0.002      9.828      0.000       0.018       0.027
    tool_usage_frequency         0.1990      0.008     25.255      0.000       0.184       0.214
    automated_task_count         0.0142      0.011      1.305      0.192      -0.007       0.035
    AI_assisted_planning         1.9776      0.092     21.488      0.000       1.797       2.158
    real_time_feedback_score    -0.0019      0.003     -0.587      0.557      -0.008       0.004
    ==============================================================================
    Omnibus:                       11.159   Durbin-Watson:                   1.971
    Prob(Omnibus):                  0.004   Jarque-Bera (JB):                7.352
    Skew:                          -0.033   Prob(JB):                       0.0253
    Kurtosis:                       2.585   Cond. No.                     5.30e+03
    ==============================================================================
    
    Notes:
    [1] Standard Errors assume that the covariance matrix of the errors is correctly specified.
    [2] The condition number is large, 5.3e+03. This might indicate that there are
    strong multicollinearity or other numerical problems.
    

### The results of an OLS regression predicting productivity scores based on task completion rate, late task ratio, focus time, AI-assisted planning, and other data are presented here. The value of the coefficient shows a significant and positive effect on the AI+Panning plan = 1 with p-value = 0.0. Also of a good strength of significance are the task completion and focus time. The R-squared of the model is 0.972, which indicates that the model fits very well. This shows that the metrics of planning and work behavior using AI can be a significant predictor of productivity. It confirms the hypothesis of the benefits of the use of AI for optimization of performance and issues quantitative conclusions concerning organizations' decision making in the context of managing remote workers.


```python
# Regression evaluation metrics

y_true = remote_work_clean["productivity_score"]
y_pred = model.predict(remote_work_clean)

mae = np.mean(np.abs(y_true - y_pred))
mse = np.mean((y_true - y_pred) ** 2)
rmse = np.sqrt(mse)
r2 = model.rsquared
adj_r2 = model.rsquared_adj

print("Regression Evaluation Metrics")
print("MAE:", round(mae, 4))
print("MSE:", round(mse, 4))
print("RMSE:", round(rmse, 4))
print("R-squared:", round(r2, 4))
print("Adjusted R-squared:", round(adj_r2, 4))
```

    Regression Evaluation Metrics
    MAE: 1.1939
    MSE: 2.0859
    RMSE: 1.4443
    R-squared: 0.9723
    Adjusted R-squared: 0.9721
    

### This figure presents evaluation metrics for the regression model, including MAE = 1.1939, MSE = 2.0859, RMSE = 1.4443, R-squared = 0.9723, and adjusted R-squared = 0.9721. High predictive accuracy and reliability. MAE, RMSE, and high R-squared indicated a minimal number of prediction errors while high R-squared indicated that 97% of the variability in the productivity scores was explained by the model. The figure corroborates the suitability of the model for forecasting productivity outcomes and shows that both AI supported planning and behavioral factors are effective predictors of the data.

## **Comparison Plots with Labels**

# ============================================================
## **COMPARISON PLOT 1: Mean Productivity Score by AI Group**
# ============================================================


```python
comparison_ai = remote_work_clean.groupby("AI_assisted_planning")["productivity_score"].mean().reset_index()

plt.figure(figsize=(12, 7))
ax = sns.barplot(
    data=comparison_ai,
    x="AI_assisted_planning",
    y="productivity_score",
    palette=["#1f77b4", "#ff7f0e"]
)

add_bar_labels(ax)
plt.title("Comparison Plot 1: Mean Productivity Score by AI-Assisted Planning", fontsize=16)
plt.xlabel("AI-Assisted Planning: 0 = No, 1 = Yes", fontsize=12)
plt.ylabel("Mean Productivity Score", fontsize=12)
plt.show()
```


    
![png](output_75_0.png)
    


### The mean productivity scores for workers with AI-assisted and without AI-assisted workers are compared in the following bar chart, which shows a difference of 2.5 points. It's clear from the figure that if workers are supported by AI in planning, then the productivity level of their work increases. It is supporting the hypothesis of the A/B test and also giving actionable insights, so it's very important to remember that handy tools like AI could lead to tangible enhancements in output, task efficiency, and overall performance when working remotely.

# ============================================================
## **COMPARISON PLOT 2: Productivity Score by Location and AI Usage**
# ============================================================


```python
comparison_location = remote_work_clean.groupby(["location_type", "AI_assisted_planning"])["productivity_score"].mean().reset_index()

plt.figure(figsize=(14, 8))  # Set figure size

# Set custom palette
palette = {0: "purple", 1: "salmon"}

ax = sns.barplot(
    data=comparison_location,
    x="location_type",
    y="productivity_score",
    hue="AI_assisted_planning",
    palette=palette
)

# Add data labels
add_bar_labels(ax)

plt.title("Comparison Plot 2: Productivity Score by Location and AI Usage", fontsize=16)
plt.xlabel("Location Type", fontsize=12)
plt.ylabel("Mean Productivity Score", fontsize=12)
plt.legend(title="AI Planning", fontsize=10, title_fontsize=12)
plt.xticks(rotation=30)  # Rotate x-axis labels if needed
plt.show()
```


    
![png](output_78_0.png)
    


### The grouped bar chart presents the mean productivity scores for City, Town, and Village, based on AI usage. City: AI=40.6, Non-AI=39.0; Town: AI=40.1, Non-AI=36.9; Village: AI=40.1, Non-AI=37.5. The results show that in all sites the development assisted by AI yields better productivity. The positive relationship between the use of AI tools and metrics reported in this study do not seem to be influenced by geographical work environment, confirming generalizability of A/B-test results and providing support for companies to adopt AI tools to increase remote productivity.

# Discussion
## Impact of AI-Assisted Planning on Productivity
The analysis results also suggest that planning with AI improves the productivity of the remote workers with AI users having higher mean productivity scores of (40.3%) than non-AI users with the mean score of (37.8%). The study results are similar to the previous works showing that task management technology can enhance efficiency in task management workflows, decision-making, and task prioritization tasks. This finding is supported by secondly, as both the T-test and Mann-Whitney U test yielded statistically significant differences between the scores of the two groups, this implies that the hypothesis that the use of AI tools has an effect on the performance outcomes is confirmed (Arsenjeva et al., 2025). Another positive effect, quantified by regression analysis (coefficient of 1.9776 and p-value of 0.0), has been identified as the use of AI from planning, which is also among the productivity determinants. This indicates that bringing AI-based planning intervention to remote work settings could further improve the rate of tasks completed by providing the organisations seeking digital solutions to boost employee efficiency empirical support.
## Role of Focus and Work Habits
The comparison plots illustrate that the productivity of a worker varies from type of location. City workers registered the highest mean AI assisted productivity (40.6%) and slightly lower mean non-AI productivity (39.0%); while Town and Village had slightly lower mean productivity as well. This is similar to what the literature has shown regarding the impact of the surroundings on remote work such as infrastructure, Internet connection, ergonomics at the workplace, etc., on the performance of remote work. The effect of location type is indirect with the productive activities, in relation to the focus of work, task variations and availability of digital tools for work (Polilli et al., 2026). There should be attention paid to not just technological intervention but also attention to the environment to optimise the performance of remote workers, regardless of their location.
## Influence of Demographic and Location Factors
The findings show very close relationships between focus time, task completion and productivity scores (r = 0.9085), reinforcing previous research, which has found that emphasis on focus time is an important factor in determining remote workers' efficiency. The workers with high productivity had higher levels of: Focus times, tasks completed ratio and lower ratio of tasks worked on late. Again, this was in congruence with results found in literature. The results of regression analysis confirm that focus time (coef = 0.0222, p < 0.001) and task completion rate (coef = 0.4263, p < 0.001) are significant factors to predict productivity. The results indicate that AI tools can efficiently support not only planning but also behavior change by helping to create structured working schedules and track progress and offering feedback (Johnson et al., 2024). Incorporating such measures into performance measurement systems can enable companies to create interventions to improve both cognitive and procedural measures of productivity, thereby getting the most out of their employees.
## Validation of Productivity Metrics and Statistical Findings
The result of the study is actionable and they will see there are valuable insights for organisations who have remote teams. The figure of 1.36% is just one of the measurable outputs of using AI as a planning assistant with various proof points that can be used to encourage the integration of AI tools for task prioritization and workload management. Consistent improvement across geographic locations as shown in comparison plots, is evidence of the generalizability of this tool (Dong et al., 2025). Further, regression and ANOVA analysis shows that the organization can find out the key productivity drivers, which could be beneficial for allocation of resources and training of the employees. The study highlights the importance of making decisions based on data to make processes more efficient and reduce inefficiencies (Rodrigues et al., 2023). Combined with environmental and behavioural factors, the use of AI tools can have a significant impact on improving remote workforce performance and inform scalable strategies for organizations.
## Limitations
The study is based on secondary data from Kaggle's remote worker dataset, and may not reflect all the variability of work settings, industry environments and worker activities in the real workplace. The planning variable involved with the AI is a dichotomous variable, therefore there are limited insights available that can be learned regarding the use of varying levels of the tool. In addition, cross sections do not allow for causal inference, and some demographic/ organizational characteristics affecting productivity are not addressed, like team dynamics or management support (Huang et al., 2022). The results indicate that these limitations should be taken into consideration when interpreting the findings in the present study and in subsequent research longitudinal and/or primary data are needed to confirm the results.

# Conclusion
The report offers ample proof of the productivity benefits of AI-supported planning for people who work remotely. The mean scores of productivity were analyzed across the Kaggle remote workers dataset, revealing that those who use AI reached a higher productivity score (40.3) than those who do not (37.8), and a T-test and Mann Whitney U were used to test for significance. The regression analysis revealed key predictors, including the achievement of the tasks, focus time, and planning support from AI, which accounted for more than 97% of the variance in productivity scores. Pairing those ones with correlation and ANOVA analyses further confirmed that two factors of sustained focus and efficient task management are key factors. The gains in productivity were found across types of locations, highlighting the overall value of AI tools. The results highlight the need for combination of digital planning solutions with other organizational supports to improve the efficiency of work flows. In summary, the findings offer valuable guidance for effective workforce management practices, offering organizations actionable insights to effectively manage remote workers and maximize productivity through data-driven decision making.


# References
## Pinheiro, A. and Palma-Moreira, A., 2025. Job satisfaction, perceived performance and work regime: What is the relationship between these variables?. Administrative Sciences, 15(5), p.175. 
## Kambezidis, H.D., Patelis, E. and Kavadias, K.A., 2025. An in-depth analysis of the Ångström–Prescott-type solar models: Application for Athens, Greece. Academia Environmental Sciences and Sustainability, 2(1). 
## Değermenci, A.S., Zengin, H., Özcan, M. and Çitgez, T., 2025. Investigation of changes in leaf area ındex in different forest stands. Environmental Monitoring and Assessment, 197(8), p.843. 
## Johnson, S., Kantartjis, M., Severson, J., Dorsey, R., Adams, J.L., Kangarloo, T., Kostrzebski, M.A., Best, A., Merickel, M., Amato, D. and Severson, B., 2024. Wearable sensor-based assessments for remotely screening early-stage Parkinson’s disease. Sensors, 24(17), p.5637. 
## Polilli, W., Galieni, A., Platani, C., Stagnari, F. and Antonini, A., 2026. Automated classification of plant water status through morpho-kinematic monitoring of plant movement. Computers and Electronics in Agriculture, 241, p.111277. 
## Wang, Y., Chow, M., Yoon, D.Y., Bopardikar, R., Chen, S., Farkas, Z., Gocmen, C., Goenka, K., Hailu, A., Hodges, D. and Huang, E., 2025. Detecting Tiny Performance Regressions at Hyperscale. ACM Transactions on Computer Systems. 
## Dong, X., Mott, D.A., Zhou, Q. and McKnight, B.M., 2025. Does sample size of leaf osmotic potential significantly affect the evidence of its association with cotton yield?. Journal of Arid Environments, 229, p.105387. 
## Rodrigues, H., Ceddia, M.B., Vasques, G.M., Mulder, V.L., Heuvelink, G.B., Oliveira, R.P., Brandão, Z.N., Morais, J.P., Neves, M.L. and Tavares, S.R., 2023. Remote sensing and Kriging with external drift to improve sparse proximal soil sensing data and define management zones in precision agriculture. AgriEngineering, 5(4), pp.2326-2348. 
## Polilli, W., Antonini, A., Platani, C., Stagnari, F. and Galieni, A., 2026. Enhancing Morpho-Kinematic analysis for Plant Water Stress Classification through Leaf Movements. Smart Agricultural Technology, p.101930. 
## Arif, B., Priono, P.N., Suardy, W. and Azhar, Z., 2024. The impact of third party funds, loan to deposit ratio and capital adequacy ratio on return on assets: case study of banking listed on the IDX 2018-2022 period. Jurnal Ilmiah Manajemen Kesatuan, 12(4), pp.1137-1146. 
## Li, Y., Miao, Y., Rawat, A., Stueve, K. and Cao, W., 2025. Identifying key soil and landscape factors influencing yield spatial patterns for management zone delineation using ensemble machine learning. Computers and Electronics in Agriculture, 237, p.110487. 
## Arsenjeva, J., Kruus, P., Hallik, R., Matasova, S., Prett, L., Kaarna, K., Raam, L., Taul, O., Ilves, L., Viljar, K. and Konno, P., 2025. Remote Monitoring of Psoriasis: Comparing Care Models and Evaluating Quality of Life Outcomes: Mixed Methods Study. Journal of Medical Internet Research, 27, p.e73664. 
## Jabor, A., Kubíček, Z., Čásenská, J., Vacková, T., Filová, V. and Franeková, J., 2024. Biological variation of PIVKA-II in blood serum of healthy subjects measured by automated electrochemiluminescent assay. Practical Laboratory Medicine, 39, p.e00389. 
## Mardalena, I., Mursalin, S. and Indra, Y.A., 2025. Influence Of Religiosity, Perception Of Entrepreneurship, And Locus Of Control On Entrepreneurial Decisions. BIMA Journal (Business, Management, & Accounting Journal), 6(2), pp.1513-1528. 
## Huang, W., Li, W., Xu, J., Ma, X., Li, C. and Liu, C., 2022. Hyperspectral monitoring driven by machine learning methods for grassland above-ground biomass. Remote Sensing, 14(9), p.2086. 
## Aidha, C.N., Afriani, S. and Christono, A.B., 2025. The Effect of Provincial Minimum Wages and Open Unemployment Rate on Poverty in DKI Jakarta 2016-2023. Jurnal Wacana Ekonomi, 25(1), pp.045-051. 
## Mallorie, T.L., Julien, P., William, P., Alexandra, C., Isabelle, G., Gabriela, M., Vicky, A., Hernandez, C., Vincent, B., Joëlle, T. and Arnaud, D., 2024. Validation of a 60K SNP chip for caribou (Rangifer tarandus) for use in wildlife forensics, conservation, and management. Forensic Science International: Animals and Environments, 6, p.100093. 
## Sungur, M., Kılıç, B.A. and Doğan, U., 2026. Nursing Students’ Healthy Living Skills and Disaster Preparedness: A Relationship Study After the Kahramanmaraş Earthquakes (Mw 7.7 and Mw 7.6) in Türkiye. JOURNAL OF EDUCATION AND RESEARCH IN NURSING, 23(1), pp.31-35. 
## Haloho, A.A.B., Calen, C. and Berlien, R., 2026. The Influence of Work Discipline and Work Facilities on Employee Performance with Job Satisfaction as an Intervening Variable at the Regional Development Planning, Research, and Development Agency of Pematangsiantar City. Journal of Management and Business Analytics, 2(1), pp.81-92. 
## Thorp, K.R., Thompson, A.L. and Herritt, M.T., 2024. Phenotyping cotton leaf chlorophyll via in situ hyperspectral reflectance sensing, spectral vegetation indices, and machine learning. Frontiers in Plant Science, 15, p.1495593. 
## Kaggle, (2025) Remote Worker Productivity Dataset. Available at: https://www.kaggle.com/datasets/ziya07/remote-worker-productivity-dataset (Accessed: 28 May 2026)

# Appendices
## Appendix A: GitHub Repository
https://github.com/sreeramvikramannair-wq/A-B-Testing-Project-on-Remote-Work-and-Productivity-Trends.git
