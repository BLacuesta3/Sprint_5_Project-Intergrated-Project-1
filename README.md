Project Title: Sprint 5 Project/ Integrated Project 1 

Project Description: 
   In this integrated project, I have used Exploratory Data Analysis in order to help the online store, 'Ice'
identify patterns that can determine whether the company's games can succeed or not.  This project
involved analyzing information about the company such as: user and expert reviews, genres, and platforms (ex: XBox, Playstation, etc,)
in order to make conclusions about patterns or trends that can be determined through company sales information.  The dataset is based
on past information that dates back to the year, 2016.  In order to examine the data for the 'Ice' company, I have used various charts 
and plots such as: bar charts, boxplots, lineplots, and histograms to display various distributions and statstics present in the dataset. 

Project Dataframe: 'games (8).csv' 

Project Tools And Libraries Used:

* pandas
  
* numpy
  
* random
  
* matplotlib
  
* scipy (module: stats)
  
* scipy.stats (function: pearsonr)

* seaborn

Project Methodology:

1) Importing The Necessary Libraries

2) Reading/ Uploading The Project Dataframe

3) Data Cleaning/ Data Preprocessing

4) Solving/ Answering Data Analysis Task: Look at how many games were released in different years. Is the data for every period significant?
    (Seaborn histogram used to solve this task.)

5) Solving/ Answering Data Analysis Task: Look at how sales varied from platform to platform.
   Choose the platforms with the greatest total sales and build a distribution based on data for each year.
   (Seaborn bar plots used to solve this task.)

6) Solving/ Answering Data Analysis Task: Find platforms that used to be popular but now have zero sales.
   How long does it generally take for new platforms to appear and old ones to fade? (Seaborn lineplots used to solve this task.)

7) Solving/ Answering Data Analysis Task: Determine what period you should take data for. To do so, look at your answers to the previous questions.
   The data should allow you to build a model for 2017. (Seaborn bar plots used to solve this task.)

8) Solving/ Answering Data Analysis Task: Build a box plot for the global sales of all games, broken down by platform.
   Are the differences in sales significant? What about average sales on various platforms? Describe your findings. (Seaborn bar plots used to solve this task.)

9) Solving/ Answering Data Analysis Task: Take a look at how user and professional reviews affect sales for one popular platform (you choose).
   Build a scatter plot and calculate the correlation between reviews and sales. Draw conclusions. (Name Of Platform Chosen: 'PS4')
   (Seaborn scatterplots used to solve this task.)

10) Solving/ Answering Data Analysis Task: Keeping your conclusions in mind, compare the sales of the same games on other platforms.
    (Seaborn bar plots and seaborn boxplots used to solve this task.)

11) Solving/ Answering Data Analysis Task:  Take a look at the general distribution of games by genre. What can we say about the most profitable genres?
    Can you generalize about genres with high and low sales? (Seaborn boxplots used to to solve this task.)

12) Solving/ Answering Data Analysis Task:
    
    For each region (NA, EU, JP), determine:
    
    * The top five platforms. Describe variations in their market shares from
      region to region. (Seaborn boxplots used to solve this task.)

    * The top five genres. Explain the difference. (Seaborn boxplots used to solve this task.)

    * Do ESRB ratings affect sales in individual regions?  (Seaborn boxplots used to solve this task.)

13) Solving Hypothesis Testing Task:

    Task/ Question Being Addressed: Test the following hypotheses:

—Average user ratings of the Xbox One and PC platforms are the same.
  ttest Used For Task: st.ttest_ind()
  ttest Result/ Task Hypothesis Conclusion: "We cannot reject null hypothesis."

—Average user ratings for the Action and Sports genres are different.
 ttest Used For Task: st.ttest_ind()
 ttest Result/ Task Hypothesis Conclusion: "We cannot reject null hypothesis."

Set the alpha threshold value yourself.

Explain:

—How you formulated the null and alternative hypotheses.

—What significance level you chose to test the hypotheses, and why.
