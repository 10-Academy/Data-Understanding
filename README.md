# Data-Understanding
Data understanding is the knowledge you have about data, the needs the data will satisfy, its content and location. There is no tool or artifact for data understanding, as it is expressed in business glossaries, data dictionaries, models and other forms of metadata or other places where information about the data is stored.

As stated by ibm in this [article](https://ibm-cloud-architecture.github.io/refarch-data-ai-analytics/preparation/data-understanding/), there are 2 key stages in Data Understanding; Data Assessment and Data Exploration.

<h4>Data Assessment</h4> <br>
The first step in data understanding is Data Assessment. This should be undertaken before the kick-off of a project as it is an important step to validate its feasibility. This task evaluates what data is available and how it aligns to the business problem. It should answer the following questions:
<ul>
  <li>What data is available?</li>
  <li>How much data is available?</li>
  <li>Do you have access to the ground truth, the values you’re trying to predict?</li>
  <li>What format will the data be in?</li>
  <li>Where does it reside?</li>
  <li>How can the data be accessed?</li>
  <li>Which fields are most important?</li>
  <li>How do the multiple data sources get joined?</li>
  <li>What important metrics are reported using this data?</li>
  <li>If applicable, how does the data map to the current method of completing the task today?</li>
</ul>

<h4> Data Exploration </h4> <br>
Once you have access to data, you can start Data Exploration. This is a phase for creating meaningful summaries of your data, this is particularly important if you are unfamiliar with the data. This is also the time you should test your assumptions. The types of activities and possible questions to ask are:

<ul>
  <li>Count the number of records – is this what you expected?</li>
  <li>What are the datatypes – will you need to change these for a machine learning model?</li>
  <li>Look for missing values – how should you deal with these?</li>
  <li>Verify the distribution of each column – are they matching the distribution you expect (e.g. normally distributed)?</li>
  <li>Search for outliers – are there anomalies in your data? Are all values valid (e.g. no ages less than 0)?</li>
  <li>Validated if your data is balanced – are different groups represented in your data? Are there enough examples of each class you wish to predict?</li>
  <li>Is there bias in your data – are subgroups in your data treated more favorable than others?</li>
</ul>

Click [here](https://ibm-cloud-architecture.github.io/refarch-data-ai-analytics/preparation/data-understanding/) to read more about the details involve at each stage of the data understanding.

## How will I use Data Understanding in my ML career
Data Understanding allows data practitioners to build better ML models, communicate useful insights and help frame business questions. It is an important skill any data practitioner should have because of it many use cases like framing a good business question that can inform the next step in any data science project. It also help understand the problem with the data and inform how to fix such problem.

## Why is it important to understand Data Understanding
I go by the saying you can not prepare what you do not understand. If you do not know what the data entails and what kind of questions you want answers to you can't get the right answers and this will negatively affect any business. 

## How Data Understaning help solve a problem
Data Understanding help solve many different problems by providing answers to questions. Questions like what is the total size of sales data? What are the features present in the advertisement data. Are there missing values in any of the columns? What kind of business question can i answer with the employee records etc. The answers gotten from these questions can then inform the business about the decision to make, next step of action and many others.

## Examples of how you probably use Data Understanding today
Making decisions: Before you decide what to do and how to do it, you must have thought about the result/consequence of taking this step instead of that step.

## What differentiate begineers from experts in this competency
- **Begineers**
  - can interpret feature definition from data description
  - can transform categorical features to numerical

- **Experts**
  - can perform feature engineering on some features
  - can interpret feature problems like why a feature has missing values and select best approach to deal with such problem
  - can select important features for the model to perform best

### Data Understanding with Codes
1. [Data Understaning 101](https://medium.com/analytics-vidhya/data-understanding-101-exploratory-data-analysis-using-python-2ad259d74a05): Here you get a hands on walkthrough of how to understand data.
2. [A Beginner’s Guide to Data Analysis in Python](https://towardsdatascience.com/a-beginners-guide-to-data-analysis-in-python-188706df5447): A step by step guide to get started with data analysis in Python
