[link to below](# using-python-for-determining-school-performance)


## Portfolio Introduction
As the field of Data Science and Analytics continues to mature, the range of business problems it can help solve is staggering. Each project in this portfolio illustrates a business problem, either real or simulated, and how applying data science technology can help solve it with solutions ranging from simple excel to sophisticated AI/Machine Learning networks. Clicking on the Titles will take you to the respective GitHub Project Respository. 

## [Using Analytics To Set Kickstarter Campaign Goals](https://github.com/tcottrell321/kickstarter-analysis)
### Applying data analytics via excel functions and graphing to past Kickstarter Campaigns can help inform goals for your new campaign. 
![](/images/kickstarterlogo.JPG)

### Situation
Rather than just winging it, the smart use of data analytics and past kickstarter campaign data -- on both successful and failed - can be used to set realistic, achievable monetary and timing goals for your new kickstarter campaign. In this project, Louise wants to create a Kickstarter Campaign to fund her new US Based Theatre Play. She estimates she will need to raise $10-12K. 

### Actions and Output Value
Using data from over 4000 past campaigns, Excel and its built-in functions were used to filter, sort, calculate, and analyze the data to gain insight to patterns, trends, and attributes leading to success. Heavy use of Excel Statistical Functions and Whisker Plots, Line Charts, and Tablular Data served as powerful tools to gain insights on how Louise can best plan her campaign.  

## [Providing Decision Support for Company Rightsizing](https://github.com/tcottrell321/Pewlett_Hackard_Analysis)
### Using SQL to perform transformation and load operations on HR data, I provided Decision Support for Senior Managers on upcoming early retirement and succession planning decisions. 
![](/images/employees2.jpg)

### Situation
A large company with over 300,000 employees needed to rightsize by offering early retirement packages while doing succession planning and mentoring of their refreshed workforce.  

### Actions and Output Value
Using CSV employee files, I used SQL and Visual Studio - plus a local PostgreSQL database - to perform an exploratory data analysis against various parameters. I designed the ERD, created the DB, loaded the data, then filtered, sorted, and cleaned the data. Finally, I built SQL queries to answer the business questions posed by Senior Managment - ultimately providing them a written report to make informed, legal, data-driven rightsizing and succession planning decisions. To promote transparency and legality, I documented each part of the process in the report so Senior Mgt could see how the target employee lists were generated. 

## [Using Python To Determine School Performance](https://github.com/tcottrell321/school_district_analysis)
### Using Python, Pandas, and Numpy I analyzed the performance of 14 schools within a single district in light of cheating. I learned techniques for dealing with invalid data. 
![](/images/schooltesting1.jpg)
### Situation
Test results from 14 individual schools in one district were analyzed, stacked ranked for comparison, then summarized for district level performance against various parameters such as Spending/Student and Class Sizes. After discovering test score cheating at one school, the data had to be cleaned and resummarized to ensure district level data integrity and results. 

### Actions and Output Value  
The student files were imported into dataframes then the data had to be cleaned for NULL data, inconsistencies in text fields, and omitting data from 9th Grade classes as it had been changed dishonestly at the school level. To do this work, a number of Python functions and methods from Python and the Pandas/Numpy libraries. The data was then analyszed to answer a number of questions from the School Board, as well as provide District Level Summary Analysis. Consideration had to be given as to how the omitted data affected overall Summary Results. Work was performed under the direction of a Senior Data Scientist who worked directly with the School Board. 
The results were summarized into a final report with District Level Summary Tables, insights and conclusions found in the data. 

## [Using AI to Help Direct Donations To Non-Profits](https://github.com/tcottrell321/AlphabetSoupChallenge)
### Can Machine Learning be used to improve the ROI of investments made in Non-Profits? In this application using TensorFlow and Scikit-Learn a Machine Learning Model was trained using sucessful past investments in Non-Profit orgranizations in order to better predict where to make future donations. 
![](/images/ai.jpg)

### Situation
AlphabetSoup provides funding to non-profit organizations. In the past, they have contributed funds to 34,299 organizations, representing about $95B. With such large sums of money involved, improving their success rate by even a small percentage could reap big payoffs in ROI. 

The AlphabetSoup Director would like to see if the application of Machine Learning or Deep Learning can find patterns in the data to help them improve their 53.2% Accuracy Rate on choosing the correct recipients to a target level of 75% or better. AlphabetSoup has provided a data file for the past recipients and noted if they achieved success, along with other parameters which they felt might be useful as a first pass analysis.

### Actions and Output Value
The problem is a classic "Binary Classification" problem, in which Applicant Non-Profits need to be separated into Successful and Non-Successful groups represented by the parameter "IS_SUCCESSFUL=1 or 0." Using Python Pandas it was determined that the DataFrame Shape is 34,299 Rows X 117 Columns. After preliminary analysis and wrangling an iterative process was used to train a Random Forest Classifier to find the optimum X parameters to achieve a greater predictive accuracy. A Benchmark RandomForest Model achieved an accuracy of 69.9%. This represents quite a significant improvement in AlphabetSoup's current approval process of 53.2% - or a 16.7% improvement. This improvement represents an additional 5700 organizations -- or $15.7B - being placed correctly with organization destined for success.

## [Improving Loan Screening Using Machine Learning](https://github.com/tcottrell321/Loan_Application_Screener)
### Peer2Peer Lending is emerging as an important tool for both lenders and borrowers and can be improved through the application of AI/Machine Learning to assess risk.    
![](/images/loans.png)

### Situation
LendingClub is a peer-to-peer lending company in which private investors can invest their own money by lending it to other individuals. Lending Club makes millions of individual loans and keeps original loan application files and if the borrower ultimately paid back the loan or defaulted.This data was stripped of borrower ID information making it anonymous, but the variables during application were kept in tact so they could be evaluated by a machine learning model.

### Actions and Output Value  
To facilitate building and testing various ML Sampling Models, a CSV file was provided for "train" and "test" data.The problem is a "Classification" problem, but its complicated by the dataset being Unbalanced. Results were achieved by iterative testing of 4 different sampling models using a structured process described in the project README file. 

Conclusions: If the objective of the LendingClub is to maximize marketshare then choosing the SMOTE Oversampling will provide the highest number of approvals for low-risk loan applicants and the lowest number of rejections on good borrowers, with a slight hit on profitability per loan by accepting a higher rate of approvals for high-risk applicants, 

If LendingClub instead wishes to maximize profitability instead of markeshare, then choosing the Random Sampling Model might be best to minimize the number of approvals on high-risk candidates at some sacrifice of rejecting good candidates.

# [#makeovermonday Tableau Visualizations](https://public.tableau.com/profile/thomas.cottrell#!/?newProfile=&activeTab=0)
![](/images/dashboard1.jpg)
Dashboards and Visualizations are a powerful way to provide realtime business updates or tell a story with data. As a member of the global Tableau Community via #MakoverMonday I am challenged each Monday to improve a VIZ using either Tableau, Power BI, Google Data Studio or other visualization tools, and publish my work to the Tableau Public Website. Each Wednesday, our work is reviewed by the Leaders so we can continue to learn and improve. Click the title above to see my evolving portfolio of VIZs.  

