# Table of Contents

1. [Installation](#Installation)
2. [Project Motivation](#Project-Motivation)
3. [File Descriptions](#File-Descriptions)
4. [CRISP-DM Process](#CRISP-DM-Process)
5. [Results](#Results)
6. [Licensing, Authors, and Acknowledgements](#Licensing,-Authors,-Acknowledgements)

## Installation

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## Project Motivation

For this project, I was interestested in using Stack Overflow data from 2019 to better understand french developers:

1. What technologies do they use and how are the technologies are asscociated with the salaries.
2. What are the developer types and the breakdown salaries that come with.
3. An investigation on the education background of french developers.


## CRISP-DM Process
In working with missing values, categorical variables, and building out my model, it was probably easy to lose sight of the big picture of the process. Let's take a quick second to recap that here, and pull together the results I have arrived through my analysis.

1. Business Understanding
What technologies do french devlopers use for work? How the salaries are associated with each catagory of technical language?
What kind of developers they are? What developer type earn the most ?
How about their education background? Are there many self-made developers? 

2. Data Understanding

Here we used the StackOverflow data to attempt to answer our questions of interest. We did 1. and 2. in tandem in this case, using the data to help us arrive at our questions of interest. 

3. Prepare Data

In order to have data focused on France, we selected the rows that with the country in France. Also, As the LanguageWorkedWith and DevType columns are results of multiple choices,thus we will have to iterate and count the value each time it occurs. Also, to asscociate the values with salaries we have to wrange the data seperatedly in order to get findings. 


4. Model Data

There was no modeling in the data, however, statistics are used to evaluate the salaries and education background. 

5. Results

Results are the findings from our wrangling and modeling. They are the answers you found to each of the questions.



## File Descriptions

There are 1 notebook available here to showcase work related to the above questions. The notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title. Markdown cells were used to assist explain the code process.

There are 6 images extracted from the notebook to showcase the findings.

## Results

The main findings of the code can be found at the post available [here](https://medium.com/@gezoe1207/how-much-do-french-developers-earn-a-year-3e79ecbe070c).

## Licensing, Authors, Acknowledgements

Must give credit to Stack Overflow for the data. You can find the Licensing for the data and other descriptive information at the Kaggle link available here. Otherwise, feel free to use the code here as you would like!
