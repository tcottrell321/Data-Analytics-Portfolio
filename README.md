# Group 1 - SQL, Excel, Python, Pandas, Numpy
![](/images/DSProcess1.JPG)

## [Project 1.1 Rightsize and Refresh Employee Base](https://github.com/tcottrell321/Pewlett_Hackard_Analysis)
Using SQL to perform TL and produce employee lists for early retirement and succession planning. 

### Situation:
A large company with over 300,000 employees needed to rightsize by offering early retirement packages while doing succession planning and mentoring of their refreshed workforce.  

### Actions and Output Value:
Using CSV employee files, I used SQL and Visual Studio - plus a local PostgreSQL database - to perform an exploratory data analysis against various parameters. I designed the ERD, created the DB, loaded the data, then filtered, sorted, and cleaned the data. Finally, I built SQL queries to answer the business questions posed by Senior Managment - ultimately providing them a written report to make informed, legal, data-driven rightsizing and succession planning decisions. To promote transparency and legality, I documented each part of the process in the report so Senior Mgt could see how the target employee lists were generated. 


## [Project 1.2 Setting Kickstarter Campaign Goals](https://github.com/tcottrell321/kickstarter-analysis)
Applying data analytics via Excel Functions and Graphing to past Kickstarter Campaigns can help inform goals for your new Campaign. 

### Situation:
Rather than just winging it, the smart use of data analytics and past kickstarter campaign data -- on both successful and failed - can be used set realistic, achievable monetary and timing goals for your new kickstarter campaign. In this project, Louise wants to create a Kickstarter Campaign to fund her new US Based Theatre Play. She estimates she will need to raise $10-12K. 

### Actions and Output Value:
Using data from over 4000 past campaigns, Excel and its built-in functions were used to filter, sort, calculate, and analyze the data to gain insight to patterns, trends, and attributes leading to success. Heavy use of Excel Statistical Functions and Whisker Plots, Line Charts, and Tablular Data served as powerful tools to gain insights on how Louise can best plan her campaign.  


## [Project 1.3 Determining School Performance](https://github.com/tcottrell321/school_district_analysis)
Using Python, Pandas, and Numpy to analyze the performance of 14 schools within a single district in light of cheating.  

### Situation:
Test results from 14 individual schools in one district were analyzed, stacked ranked for comparison, then summarized for district level performance against various parameters such as Spending/Student and Class Sizes. After discovering test score cheating at one school, the data had to be cleaned and resummarized to ensure district level data integrity and results. 

### Actions and Output Value:  
The student files were imported into dataframes then the data had to be cleaned for NULL data, inconsistencies in text fields, and omitting data from 9th Grade classes as it had been changed dishonestly at the school level. To do this work, a number of Python functions and methods from Python and the Pandas/Numpy libraries. The data was then analyszed to answer a number of questions from the School Board, as well as provide District Level Summary Analysis. Consideration had to be given as to how the omitted data affected overall Summary Results. Work was performed under the direction of a Senior Data Scientist who worked directly with the School Board. 
The results were summarized into a final report with District Level Summary Tables, insights and conclusions found in the data. 


# [Group 2 Visualizations Portfolio Using Tableau](https://public.tableau.com/profile/thomas.cottrell#!/?newProfile=&activeTab=0)
![](/images/DSProcess2.JPG)

Visualizations are a powerful way to tell a story with data. As a member of the global Tableau Community via #MakoverMonday I am challenged each Monday to improve a VIZ using either Tableau, Power BI, Google Data Studio or other visualization tools, and publish my work to the Tableau Public Website. Each Wednesday, the Community of several hundred Data Analysts gets feedback from Leaders in the Community. 

# Group 3 - Aspirational Projects in Machine Learning
![](/images/DSProcess3.JPG)

## [Project 3.1 Investing in Non-Profits](https://github.com/tcottrell321/AlphabetSoupChallenge)
Using TensorFlow and Scikit-Learn with Python to improve investment accuracy in Non-Profits  

### Situation:
AlphabetSoup provides funding to non-profit organizations. In the past, they have contributed funds to 34,299 organizations, representing about $95B. With such large sums of money involved, improving their success rate by even a small percentage could reap big payoffs in ROI. 

The AlphabetSoup Director would like to see if the application of Machine Learning or Deep Learning can find patterns in the data to help them improve their 53.2% Accuracy Rate on choosing the correct recipients to a target level of 75% or better. AlphabetSoup has provided a data file for the past recipients and noted if they achieved success, along with other parameters which they felt might be useful as a first pass analysis.

### Actions and Output Value:  
The problem is a classic "Binary Classification" problem, in which Applicant Non-Profits need to be separated into Successful and Non-Successful groups represented by the parameter "IS_SUCCESSFUL=1 or 0." Using Python Pandas it was determined that the DataFrame Shape is 34,299 Rows X 117 Columns. After preliminary analysis and wrangling an iterative process was used to train a Random Forest Classifier to find the optimum X parameters to achieve a greater predictive accuracy. A Benchmark RandomForest Model achieved an accuracy of 69.9%. This represents quite a significant improvement in AlphabetSoup's current approval process of 53.2% - or a 16.7% improvement. This improvement represents an additional 5700 organizations -- or $15.7B - being placed correctly with organization destined for success.
