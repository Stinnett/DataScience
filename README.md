# DataScience
Working with big data sets to play with different data science concepts.

Project description:
In the past several years, there has been tremendous growth in peer-to-peer (P2P) lending.  There are many websites that facilitate this; the largest few of these now have over a $1B marketcap.  This sites give users the option to either apply for a loan or to invest in a loan.  

For the investor, the sites generally provide much (anonymized) detail about the applicant.  Income, whether they have a mortgage or if they rent, location, credit history, and so on.  These sites also typically have their own rating system for applicants that combines this information to give an idea of how likely they are to actually pay off their loan (users with better ratings also get better interest rates).  

These sites raise many questions:

1) Using machine learning or regression techniques on the supplied data, how well can we predict whether loans will default or not?

2) Given an algorithm's accuracy, what is an optimal investing strategy as a function of acceptable risk?

3) How do the above results compare to human performance ("gut instinct") on the site? How do they compare against the provided automated investing on certain sites?

4) While most of the information provided by these sites is the same, there are some differences (e.g. ).  Is it possible the different information on one site allows us to make better decisions about investing?  

In this repo, I intend to answer these questions, with major emphasis on question 4.  Specifically, I plan to initially compare Lending Club and Prosper, two of the biggest P2P personal-loan sites.  Eventually, I'd like to add others as well.

The initial data for this project was downloaded pre-packaged from Lending Club (https://www.lendingclub.com/info/download-data.action)(~700MB).  They do provide an API to fetch current loan information, which will be useful in the future.  Similarly, Prosper also has a public API.


----------------------------------------------------------------------------------------------------------------------------------
Repo Contents
  demo/Project_Demo.ipynb: notebook exploring the Lending Club dataset, with visualizations of what determines interest rate and which   loans have defaulted.
  
----------------------------------------------------------------------------------------------------------------------------------
Data is currently hosted locally only; eventually it will be moved to an AWS S3 bucket.
