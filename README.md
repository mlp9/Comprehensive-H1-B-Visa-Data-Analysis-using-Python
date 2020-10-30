# Comprehensive-H1-B-Visa-Data-Analysis-using-Python
H-1B is a visa category in the United States of America under the INA, section 101(a)(15)(H) which allows U.S. employers to employ foreign workers. The first step employer must take to hire a foreign worker is to file the Labor Condition Application. In this project, we will analyze the data from the Labor Condition Application.

The H-1B Dataset selected for this project contains data from employer’s Labor Condition
Application and the case certification determinations processed by the Office of Foreign
Labor Certification (OFLC) where the date of the determination was issues on or after
October 1, 2016 and on or before June 30, 2017.
The Labor Condition Application (LCA) is a document that a perspective H-1B employer
files with U.S. Department of Labor Employment and Training Administration (DOLETA)
when it seeks to employ non-immigrant workers at a specific job occupation in an area of
intended employment for not more than three years.

## Goal of the Project:

Our project focuses on exploring and analyzing important factors, such as geography
information, industry, company and position information, that influence the H1B lottery,
generating insights and ideas on this escalating situation.

## Questions of Interest
● What type of jobs is more likely to hire non-immigrant workers under the H-1B visa
program?

● Does average salary for jobs under the H-1B visa program vary largely among different job
positions? And different regions?

● What are the top employers that sponsor the most number of H1B jobs in the U.S.? And in
Maryland?

● Which state has the highest number of applicants?

● Does having a H1B dependent affect the case status?

## Data Processing and Analysis

The data we are using for our analysis is H1B filing data from Office of Foreign Labor Certification
(OFLC). H-1B is a visa category in the United States of America under the INA, section
101(a)(15)(H) which allows U.S. employers to employ foreign workers. The first step employers must
take to hire a foreign worker is to file the Labor Condition Application.Our data has multiple attributes
like the case number, the job title details, the salary details etc. We are trying to use these multiple
attributes to see how these affect the case status of an application submitted by the employer to hire
non-immigrant workers under the H-1B visa program.
We are acquiring the data from Kaggle. The original dataset is from the Office of Foreign Labor
Certification (OFLC). OFLC is a division of the U.S. Department of Labor. The main duty of OFLC is
to assist the Secretary of Labor to enforce part of the Immigration and Nationality Act (INA), which
requires certain labor conditions exist before employers can hire foreign workers. focused at helping employers and applicants understand the process of getting LCA approval. We have performed features exploration and analysis to gather insights on how they affect the case status.

## Data Processing Tasks
● Data transformation: There are several categorical variables like visa status, which we
need to convert to numeric values for modelling.

● Data selection: The data consist of EB visas so we remove all the useless columns and
keep the data columns relevant to our analysis, that is H1B data.

● Managing missing data: There are several columns that have missing values, such as
employment start date, job title etc. So we clean them by filling or dropping those rows.

● Reshaping data: The wage column has inconsistent data, some of them has hourly
wage, weekly wage, some has annual wage. So we convert them to the same wage
level. This makes it easier to work with.

● Text processing: We replace names bi-weekly, month and week by year as we convert
all the wages to annual rate.

## Data Analysis
We are going to use interactive plots including bar plots, line charts, histograms to display
statistics descriptions, and maps to show geographical results allowing us to hover over the plot
for more details. For example, to show the number of applications per state, we will apply the bar
chart to show the numbers before using a heat map to capture results in every state.

Our jupyter notebook also received the “best notebook” badge from our professor as we did a good job documenting the notebook along with the code. 
