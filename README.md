<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>
<h3 align="center"><a href='https://www.udacity.com/course/data-analyst-nanodegree--nd002'> Udacity Data Analyst Nanodegree </a></h3>
<h4 align="center">Project 3: Communicate-Data-Findings</h4>

## Table of Contents
- [Installation](#installation)
- [Project Motivation](#motivation)
- [Project Overview](#po)
- [Project Details](#pd)
  - [Choose your Dataset](#choose)
- [Dataset](#dataset)
- [Results](#results)
- [Summary of Findings](#Sof)
- [Key Insights for Presentation](#kip)
- [Why this project?](#p) 
- [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
This project is written in Python 3 and is intended to be completed using the google colab notebooks or Jupyter Notebooks IDE. It is strongly advised that you install Python using the [Anaconda distribution](https://www.anaconda.com/distribution/), as the distribution includes all necessary Python libraries as well as Jupyter Notebooks. This project is expected to make use of the libraries listed below:

- Numpy
- Pandas
- Matplotlib
- Seaborn

## Project Motivation <a name="motivation"></a>

This is an Udacity Nanodegree project. I was interested in using Prosper Loan Data to better understand : </br>
- Univariate Exploration:
  - Loan status
  - Term
  - Employment Status
  - Total prosper loans
  - Stated Monthly Income
- Bivariate Exploration:
  - Loan status and Prosper Rating
  - Loan status and Listing category
- Multivariate Exploration:
  - Loan Original Amount, Loan Status and Prosper Rating
  - Loan Original Amount, Loan Status and Listing Category
  
### Project Overview <a name="po"></a>

This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In the first part, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables. In the second part, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.


### Project Details <a name="pd"></a>

This project is divided into two major parts. In the first part, you will conduct an exploratory data analysis on a dataset of your choosing. You will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part should be structured, going from simple univariate relationships up through multivariate relationships, but it does not need to be clean or perfect. There is no one single answer that needs to come out of a given dataset. This part of the project is your opportunity to ask questions of the data and make your own discoveries. It’s important to keep in mind that sometimes exploration can lead to dead ends, and that it can take multiple steps to dig down to what you’re truly looking for.

In the second part, you will take your main findings from your exploration and convey them to others through an explanatory analysis. To this end, you will create a slide deck that leverages polished, explanatory visualizations to communicate your results. This part of the project should make heavy use of the first part of the project. 

#### Step 1.1: Choose your Dataset <a name="choose"></a>

First, you will choose a dataset from the Dataset Options.

**Quick List Below:**

Dataset Options

* [Ford GoBike System Data](https://www.google.com/url?q=https://www.fordgobike.com/system-data&sa=D&ust=1554486256012000)
* [Flights](https://www.google.com/url?q=http://stat-computing.org/dataexpo/2009/the-data.html&sa=D&ust=1554486256017000)
* [Loan Data from Prosper](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000) with [Prosper Data Dictionary to Explain Dataset's Variables](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000)
* [PISA Data](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1554482573645000) with [PISA Data Dictionary to Explain Dataset's Variables](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv&sa=D&ust=1554482573645000)


### Dataset Chosen <a name="dataset"></a>
This data set contains information on peer to peer loans facilitated by credit company Prosper. There are 113,937 loans with 81 variables from LoanStatus, StatedMonthlyIncome to EmployementStatus.
the data can be found in :  [link](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv).
variable definitions : [link](https://docs.google.com/spreadsheets/u/0/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing).

 
### Results <a name="results"></a>

* Most of the loans in the data set are actually current loans. Past due loans are split in several groups based on the length of payment delay. Other big part is completed loans, defaulted loans compromise a minority, however chargedoff loans also comporomise a substanial amount.
<p align = "center">
  <img src="Results/Count of different loan status.PNG">
</p>
* The majority of borrowers are employed and all other categories as small part of borrowers. In small Group full time has highest, after that self empolyed are there and so on.
<p align = "center">
  <img src="Results/Count of different employement status.PNG">
</p>
* As for the monthly income we can see that the plot is skewed to the right with the mode (most frequent income) is about 5000. 
<p align = "center">
  <img src="Results/Monthly income of the borrowers.PNG">
</p>

## Summary of Findings <a name="Sof"></a>

While exploring the data i found that most individuals who are given loans are employed with a loan duration of 36 month on average, as well we found that the these borrowers on average have 5000 monthly income which augmented their chances on getting these loan's.
The primary loan category was debt followed by home improvement which was surprising.

## Key Insights for Presentation <a name="kip"></a>
i have chosen a couple of plot that can depict the results that i found in my exploratory analysis (what kind of status does the borrowers needs to augment the chances of getting a loan/number of investor).

At first, we started by introducing the employement status for the borrowers (which we found that the majority are employed). After that, we went to see the loan status, and lastly we presented the monthly income stated by the borrowers. i have plotted these findings using countplots and histograms and i simplified them as much as i can.
   
### Why this project? <a name="p"></a>

Data visualization is an important skill that is used in many parts of the data analysis process. **Exploratory** data visualization generally occurs during and after the data wrangling process, and is the main method that you will use to understand the patterns and relationships present in your data. This understanding will help you approach any statistical analyses and will help you build conclusions and findings. This process might also illuminate additional data cleaning tasks to be performed. **Explanatory** data visualization techniques are used after generating your findings, and are used to help communicate your results to others. Understanding design considerations will make sure that your message is clear and effective. In addition to being a good producer of visualizations, going through this project will also help you be a good consumer of visualizations that are presented to you by others.


## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Must give credit to Udacity for the data. You can find the Licensing for the data and other descriptive information at the Udacity Website.
