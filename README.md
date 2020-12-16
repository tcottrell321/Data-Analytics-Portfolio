![](/images/ThomasCottrell3.png)
[My Story](#my-story)
## <a id="#portfolio-introduction"></a>
## Portfolio Introduction
As the field of Data Science and Analytics continues to mature, the range of business problems it can help solve is staggering. Each project in this portfolio illustrates a business problem, either real or simulated, and how applying data science technology can help solve it with solutions ranging from simple excel to sophisticated AI/Machine Learning networks. To see more details and the GitHub code repository, click on the Blue Titles below. 

In addition to the GitHub repository, there is a Tableau Public repository containing a sample of Visualizations.   
[Link To #makovermonday Tableau Visualizations](#makeovermonday-tableau-visualizations)

## [Using Analytics To Set Kickstarter Campaign Goals](https://github.com/tcottrell321/kickstarter-analysis)
### Applying data analytics via excel functions and graphing to past Kickstarter Campaigns can help inform goals for your new campaign. 
![](/images/kickstarterlogo.JPG)

### Situation
Rather than just winging it, the smart use of data analytics and past kickstarter campaign data -- on both successful and failed - can be used to set realistic, achievable monetary and timing goals for your new kickstarter campaign. In this project, Louise wants to create a Kickstarter Campaign to fund her new US Based Theatre Play. She estimates she will need to raise $10-12K. 

### Actions and Output Value
Using data from over 4000 past campaigns, Excel and its built-in functions were used to filter, sort, calculate, and analyze the data to gain insight to patterns, trends, and attributes leading to success. Heavy use of Excel Statistical Functions and Whisker Plots, Line Charts, and Tablular Data served as powerful tools to gain insights on how Louise can best plan her campaign.  

## [Tracking COVID-19 In San Mateo County, CA](https://github.com/tcottrell321/COVID-19_Tracking_San_Mateo_County)
### Using an excel spreadsheet and data from the San Mateo County Health site, a single stacked-bar graph is produced to better inform residents.  
![](/images/COVID_image.jpg)

### Situation
The San Mateo County Health Dept publishes COVID-19 updates on their website but key data needed by citizens to make stay-at-home decisions is distributed across multiple web pages and hard to find.  

### Actions and Output
Using a simple excel spreadsheet, data is transcribed from a number of different pages on the County website to bring all critical data in one place which can support citizen's shelter-in-place decisions. I update the data once per week and post the graph on facebook for family and friends. 

## [Providing Decision Support for Company Rightsizing](https://github.com/tcottrell321/Pewlett_Hackard_Analysis)
### Using SQL to perform transformation and load operations on HR data, I provided Decision Support for Senior Managers on upcoming early retirement and succession planning decisions. 
![](/images/employees2.jpg)

### Situation
A large company with over 300,000 employees needed to rightsize by offering early retirement packages while doing succession planning and mentoring of their refreshed workforce.  

### Actions and Output Value
Using CSV employee files, I used SQL and Visual Studio - plus a local PostgreSQL database - to perform an exploratory data analysis against various parameters. I designed the ERD, created the DB, loaded the data, then filtered, sorted, and cleaned the data. Finally, I built SQL queries to answer the business questions posed by Senior Managment - ultimately providing them a written report to make informed, legal, data-driven rightsizing and succession planning decisions. To promote transparency and legality, I documented each part of the process in the report so Senior Mgt could see how the target employee lists were generated. 

## <a id="#using-python-to-determine-school-performance"></a>  
## [Using Python To Determine School Performance](https://github.com/tcottrell321/school_district_analysis)

### Using Python, Pandas, and Numpy I analyzed the performance of 14 schools within a single district in light of cheating. I learned techniques for dealing with invalid data. 
![](/images/schooltesting1.jpg)
### Situation
Test results from 14 individual schools in one district were analyzed, stacked ranked for comparison, then summarized for district level performance against various parameters such as Spending/Student and Class Sizes. After discovering test score cheating at one school, the data had to be cleaned and resummarized to ensure district level data integrity and results. 

### Actions and Output Value  
The student files were imported into dataframes then the data had to be cleaned for NULL data, inconsistencies in text fields, and omitting data from 9th Grade classes as it had been changed dishonestly at the school level. To do this work, a number of Python functions and methods from Python and the Pandas/Numpy libraries. The data was then analyszed to answer a number of questions from the School Board, as well as provide District Level Summary Analysis. Consideration had to be given as to how the omitted data affected overall Summary Results. Work was performed under the direction of a Senior Data Scientist who worked directly with the School Board. 
The results were summarized into a final report with District Level Summary Tables, insights and conclusions found in the data. 

## [Using AI to Help Direct Donations To Non-Profits](https://github.com/tcottrell321/AlphabetSoupChallenge)
### In this application using TensorFlow and Scikit-Learn, machine learning was used to better predict where to make future donations saving $15.7B.  
![](/images/ai.jpg)

### Situation
AlphabetSoup provides funding to non-profit organizations. In the past, they have contributed funds to 34,299 organizations, representing about $95B. With such large sums of money involved, improving their success rate by even a small percentage could reap big payoffs in ROI. 

The AlphabetSoup Director would like to see if the application of Machine Learning or Deep Learning can find patterns in the data to help them improve their 53.2% Accuracy Rate on choosing the correct recipients to a target level of 75% or better. AlphabetSoup has provided a data file for the past recipients and noted if they achieved success, along with other parameters which they felt might be useful as a first pass analysis.

### Actions and Output Value
The problem is a classic "Binary Classification" problem, in which Applicant Non-Profits need to be separated into Successful and Non-Successful groups. Using the Pandas library, a preliminary analysis was performed and the data wrangled to define the relevant parameters to train a Random Forest Classifier. A Benchmark RandomForest Model achieved an accuracy of 69.9%. This represents quite a significant improvement in AlphabetSoup's current approval process of 53.2% - or a 16.7% improvement. This improvement represents an additional 5700 organizations -- or $15.7B - being placed correctly for success.

## [Improving Loan Screening Using Machine Learning](https://github.com/tcottrell321/Loan_Application_Screener)
### Peer2Peer Lending is emerging as an important tool for both lenders and borrowers and can be improved through the application of AI/Machine Learning to assess risk.    
![](/images/loans.png)

### Situation
LendingClub is a peer-to-peer lending company in which private investors can invest their own money by lending it to other individuals. Lending Club makes millions of individual loans and keeps original loan application files and if the borrower ultimately paid back the loan or defaulted.This data was stripped of borrower ID information making it anonymous, but the variables during application were kept in tact so they could be evaluated by a machine learning model.

### Actions and Output Value  
To facilitate building and testing various ML Sampling Models, a CSV file was provided for "train" and "test" data.The problem is a "Classification" problem, but its complicated by the dataset being Unbalanced. Results were achieved by iterative testing of 4 different sampling models using a structured process described in the project README file. 

Conclusions: If the objective of the LendingClub is to maximize marketshare then choosing the SMOTE Oversampling will provide the highest number of approvals for low-risk loan applicants and the lowest number of rejections on good borrowers, with a slight hit on profitability per loan by accepting a higher rate of approvals for high-risk applicants, 

If LendingClub instead wishes to maximize profitability instead of markeshare, then choosing the Random Sampling Model might be best to minimize the number of approvals on high-risk candidates at some sacrifice of rejecting good candidates.

## <a id="#makeovermonday-tableau-visualizations"></a> 
# [#makeovermonday Tableau Visualizations](https://public.tableau.com/profile/thomas.cottrell#!/?newProfile=&activeTab=0)
### Dashboards and Visualizations are a powerful way to provide realtime business updates or tell a story with data. 
![](/images/dashboard1.jpg)
As a member of the global Tableau Community via #MakoverMonday I am challenged each Monday to improve a VIZ using either Tableau, Power BI, Google Data Studio or other visualization tools, and publish my work to the Tableau Public Website. Each Wednesday, our work is reviewed by the Leaders so we can continue to learn and improve. Click the title above to see my evolving portfolio of VIZs.  

## <a id="#my-story"></a> 
### My Story
Over the last few years, I have had the good fortune of serving world-class companies such as Tesla, SolarCity, Saba Software, and Hewlett-Packard. I have helped build new markets or disrupt legacy; launch new products and expand the demographic base; re-engineer manufacturing processes, and refine the customer experience. 

My unique skill is moving fluidly between business leaders, software developers, and customers to seek out and interpret relevant data and put that data into actionable improvements - be it products, processes, or services to better serve customers. 

Although currently, I best identify as a Busines Data Analyst, I’ve conducted similar work under the following titles:

1)	Business Intelligence Analyst
2)	Program Manager
3)	Sales Engineer
4)	Sales Operations and Analytics Director
5)	Customer Support Manager
6)	Business Development Manager
7)	Scrum Master
8)	Product Manager

Across these roles, regardless of the size or market of the business, I have observed one common thread to success; that is, that your business leaders and team members must:

1)	Harness the power of data to drive every decision. 
2)	Have a clear idea of how their teams are performing against the right KPI’s. 
3)	Know what problems they need to solve to get their team performance, product or service, or Customer understanding to the next breakthrough level. 
4)	Know what problems Not to solve. 
5)	Leverage the data around them and transform it into accurate, timely, insightful reports, visualizations, dashboards, and “predictive analysis” that helps guide them in real-time to achieve department and company goals.    

In each position I held, be it Sales, Manufacturing, R&D, or Customer Support, I looked to the relevant data for stories and insights so I might take actions for improvement. As Data Science and the toolset became ever more capable, my skills and experience developed within two domains: first, Business Analysis. Second, Data Science and Analytics, applying both to the company’s processes, products, or customer experience to improve results. 

Because of the rapid development in Data Science, I decided in 2019 to level up by attending an immersive, full-time 6-month program in Data Science and Analytics at UC Berkeley School of Information. One of the best programs in the country, and graduating with honors, I was introduced to a broader array of Data Science’s most advanced tools through project-based learning – some of which you can see on my GitHub Portfolio at tomcottrell.com. 

The core tools I favor and continue learning about every day are:

1)	SQL for interacting with the source of data.
2)	Python, Pandas, Numpy, Matplotlib, and Scikit-Learn for data wrangling and data exploration.
3)	Tableau, Excel, and Power BI for analysis and visualizations. 
4)	Tensor Flow and Scikit-Learn for some exploratory Machine Learning projects I am doing. 
5)	Google Co-Labs or AWS cloud-based servers for ML projects and their advanced GPUs/CPUs.  
6)	And with Agile versus Waterfall proving to be the development methodology of choice, these skills are essential as well.

Other useful tools exist, and with Google Search, W3, and Stack Overflow, it is common to add technologies rapidly as needed on-the-job. 

Whatever stage your business is in – startup, pivoting, midsize, or multi-national -- I have been there and helped leaders achieve better results. 

What are your biggest problems and barriers to growth or profitability? Let’s have a conversation and articulate your pain points and opportunities to see if I can help. 

Here’s to your success!

[return to portfolio of projects](#portfolio-introduction)
