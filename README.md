# An Introduction to Data Science and Analytics

If you are curious about data, or wish to acquire your first role as a Data Scientist, this repository is for you. Although this field may sound daunting, especially if you are new to the world of tech, the good news is that this introduction has been written for those with no prior knowledge. So whether you have many years of experience in the field, are just starting out or have wanted to get into this sector and don't know how, this short course is for you.

In this course we will cover the following sections:

- Defining Data Science and Analytics
- Data Science Components
- Applications

I hope you enjoy this repository as much as I have creating it, and showing it to students and colleagues just like you.

## Defining Data Science and Analytics

In this section, we will cover:

- What is Data Science and Analytics?
- Why Data Science and Analytics?
- Business Intelligence Vs Data Science.
- Life cycle of Data Science.

Data science is an interdisciplinary field that uses scientific methods, processes, algorithms, and systems to extract knowledge and insights from structural and unstructred data. Data science is a process, and not an event. The process is uncovering the insights and trends buried in the data. Exploring the data, manipulating the data, asking the right questions about the data, and finding the right answers is the responsibility of a Data Scientist.

Data analytics involves answering questions generated for better business decision making. It involves compiling and analysing the data to support decion making.

Sometimes, it in unclear what the difference is between a Data Analyst and Data Scientist. After all, don't they both just analyse data? And if that's your thought process, you are not alone. The below briefly distinguishes between the two:

Data Analyst:
- Business Administration
- Exploratory Data Analysis

Data Scientist:
- Exploratory Data Analysis
- Building Algorithms
- Data Product Engineering

Data science and analytics are important for making prudent decisions, identifying opportunities and business growth. Applications of data science and analytics include health, energy, finance, and ecommerce. In the health sector, we can analyse patient data to understand illnesses and prevent future occurence. This is predictive modelling.

The below briefly distinguishes between Business Analytics and Data Science:

Data Science:
- Data Sources: Structured and unstructured data.
- Results: Generates insights but not necessarily towards business decisions.
- Tools: Python, SQL, Hadoop, R, NoSQL, Rapid Miner .. etc.
- Methodology: Statistics, Machine Learning, Graph Analysis.

Business Analytics:
- Data Sources: Structured data.
- Results: Generated insights are important for decision making.
- Tools: Oracle BI, Power BI, Excel, Tableau, Looker, SQL DB ... etc.
- Methodology: Statistics and visualisations.

Below, we discuss the life cycle of data science and analytics. In a nutshell, this life cycle takes the following process:

- Data Discovery: This is first stage, in this stage we understand the business requirements, specifications and priorities.
- Data Preperation: Data collection, exploration, and processing. In this step, the data is ready for use.
- Model Planning: Determining the methods and techniques to achieving the tasks.
- Model Building: Here is where we build our model. Models include regression, classification, clustering ... etc.
- Results Communication: In this step, we communicate our results to key decision makers, stakeholders and those involved.
- Measuring Effectiveness: In this last step, we evaluate the effectiveness of the process.

## Data Preparation and Cleansing

In this section, we will cover:

- Fundamental Concepts of Data.
- Computational Tools.
- Statistics & probability.
- Machine Learning.
- Big Data Analytics.
- Communicating Insights.

**Tabular Data:** A table is an arrangement of data in rows and columns, or possibly in a more complex structure. Tabular data is data that is structured into rows, each of which contains information about some occurence. A common file format is *Comma Seperated Values* or *CSV*. Columns go from left to right, but rows go from top to bottom.

**Data Types:** A data type is the particular kind of data item, as defined by either the values it can take, the programming language used, or the operations that can be performed on it. There are two main data types, they are *Categorical* and *Numerical*.

**Categorical Data Type:** A Categorical data type is a data type that is assigned a category. In this data type, we have *Nominal* and *Ordinal* data types. For instance, if we had a criteria that everyone who get above 75% in an exam has passed while the other have failed, this is a Nominal data type. This is because we have two categories, passed or failed — they have no particular order. For Ordinal data types, we have ordered categories. For instance, having a grading critera where A is the highest grade, followed by B, then C ... etc. Another example of ordinal categorical data is clothing sizes, i.e. X-Large, Large, Medium ... etc.

**Numerical Data Type:** A Numerical data type is a data type that takes a numerical value. In this data type, we have *Discrete* and *Continuous* data types. Discrete data usually counts quantities, whereas Continuous data is used to measure. For instance, the amount of people in a room (5 people), age (35 years old), and amount of t-shirts on the shelf (10 shirts). Continuous data on the other hand can take all values, for instance, the length of grass (4.67cm), the time taken to complete a task (4 hours, 34 minutes, 7.24 seconds), and the weight of a person (78.435 KG).

**Exploration Data Analysis:** In statistics, exploratory data analysis is an approach to analysing data sets to summarise their main characteristics, often with visual methods. It is a critical process of performing initial investigation on the data to discover trends and patterns. The process allows for hypothesis testing, checking assumptions with the use of statistical, and graphical representation.

**Data Cleaning:** This critical step involves detecting and fixing corrupt and innacurate record instances. Some of these innacurate record instances include testing missing values, proper formatting, fixing inconsistent data formats, and removing duplicate records.

**Python:** Python is an interpreted, high-level and general-purpose programming language, that was created in the 90's. Toady, it's a very popular programming language for analysis due to the rise and built-in easy to use packages.

Advantages of using python:

- Easy to read index.
- Efficient to write production-based code.
- Skills are transferable.

Popular libraries include Pandas, NumPy, Matplotlib, Scikit-Learn, Tensorflow ... etc.

**R:** R is the statistical language of choice throughout academia. It's widely used among statisticians and data miners for developing statistical software and data analysis.

Advantages of using R:

- Majorly designed for statistical computing.
- Robust ecosystem of computing packages.
- Used in academics and research.

Popular libraries include ggplot2, Shiny, Tidyverse ... etc.

**SQL:** Structured Query Language is an easy to use language for data analytics. It operates through declarative statements. It is mainly used to communicate with databases, quest data, add new records and maintain the database.

Advantages of using SQL:

- Access to multiple tables.
- Easy to understand.
- Ability to query large datasets.

Relational Database Management Systems - MySQL, PostgreSQL, Oracle DB.

Computational Tools include:

- Power BI
- Tableau
- Excel
- Google Sheets
- Jupyter Notebook
- Rstudio Desktop

**Statistics and Probability:** Probability is the science of uncertainty. Statistics is the science of exploring a collection of datasets to find different hidden patterns and trends. There are two types of analysis, they are *Descriptive* and *Inferential*.

**Descriptive:** This type of analysis is focused on describing a large collection of datasets with charts and tables, but does not attempt to draw conclusions about the population from the which the sample was taken.

**Inferential:** This type of analysis is focused on exploring the data further, which allows to test a hypothesis and draw conclusions about the data.

**Machine Learning:** Machine Learning is a method of data analysis that automates analytical model building. Using algorithms that iteratively learn from data, machine learning allows computers to find hidden insights without being explicitly programmed where to look.

Traditional Programming: 
 - Input: Data + Program
 - Output: Data output

Machine Learning:
  - Input: Data + Output
  - Output: Program

**Supervised Learning:** Supervised Learning (SL) is the machine learning task of learning a function that maps an input to an output based on example input-output pairs. It infers a function from labelled training data consisting of a set of training examples. In supervised learning, each example is a pair consisting of an input object (typically a vector) and a desired output value (also called the supervisory signal). Types of Supervised Learning include *Regression* and *Classification*.

**Regression:** Examples of regression include forecasting, predictions, process optimisation, and new insights.

**Classifications:** Examples of classification include fraud detection, image classification, customer retention, and diagnostics.

**Unsupervised Learning:** Unsupervised Learning is a type of algorithm that learns patterns from untagged data. The hope is that through mimicry, which is an important mode of learning in people, the machine is forced to build a compact internal representation of its world and then generate imaginative content from it. Types of Supervised Learning include *Clustering* and *Dimensionally Reduction*.

**Clustering:** Examples of clustering include customer segmentation, targetted marketing, and recommended systems.

**Dimensionality Reduction:** Examples of dimensionality reduction include big data visualisation, meaningful compression, structure discovery and feature elicitation.

**Reinforcement Learning:** Reinforcement learning is a machine learning training method based on rewarding desired behaviors and/or punishing undesired ones. In general, a reinforcement learning agent is able to perceive and interpret its environment, take actions and learning through trial and error. Reinforcement Learning is less supervised which depends on the agent in determining the output. The input data in Supervised Learning in labelled data. Whereas, in Unsupervised Learning the data is unlabelled. The data is not predefined in Reinforcement Learning.

**Reinforcement Learning:** Examples of reinforcement learning include robot navigation, skills aquisition, learning tasks, game AI, and real-time decisions.

**Communicating Insights:** Story telling is an important part of the analytics framework, as it cna drive audiences engagement and translate insights to actions. Data professionals often need to employ effective methods to interpret and communicate findings to decision makers and stakeholders.

Typical methods include:

- Appropriate contextualisation of data.
- Detailed and compelling narrative.
- Use data visualisation techniques.
- Conclusions/summaries: Objectives, methodology, strategy, results, and actions.

