# Module 1 Final Project

## Brad Ellisor and Bryan Santos

## Introduction

At the end of Module 1 of Flatiron School's Data Science program, we were tasked with completing a Final Project demonstrating the skills we learned throughout our first three weeks. This project encapulates skills including:

* Python
* Webscraping
* API Calls
* Python Libraries: Pandas, Numpy, Matplotlib, and Seaborn
* Data Cleaning
* Data Visualization

## The Project

Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. They have hired you to help them better understand the movie industry.
Your team is charged with doing data analysis and creating a presentation that explores what type of content is currently doing the best at the box office. You must then translate those findings into actionable insights that the CEO can use when deciding what type of content they should be creating.

## Project Checklist:

- Pull data from at least 2/3 sources (1 data source per team member)
- Develop a pipeline for your data, from API/scraping to dataframe. Save down your clean data as .csv(s)
- Generate descriptive statistics to compare the success of different content 
- A slideshow presentation that entails the following:
- The purpose of your analysis and why it matters
- 4 well labeled visualizations created using Matplotlib/Seaborn
- 2 meaningful summary tables (do not copy and paste results from Pandas)
- Give at least two actionable insights (What type of content should they be looking to
produce? What should the budget requirements be? Should they recruit certain actors for their content?)

## Posted to git repo:
- README.me
- Python files and Jupyter notebooks with clean and commented code
* api_final, 
* scraping_final,
* and analysis_final
- A link to our Google slide show



## Objectives

Our objectives for the project:

* Collect Data using webscraping and API calls and clean it in order to analyze the Data.
* Create visualizations from the data in order to come up with a recommendation.
* Use the insight and Visualizations from our data to present clear and concise recommendations.
* Timely completion of deliverables

# Questions 
* How do the most successful movies utilize existing IP or are they completely original?
* What are the most successful genres of the last decade?
* Does hiring popular actors and directors have an impact on the success of a film?
* Assuming the above statement is true, is it enough to for the quality of the film?

# The Dataset
We used a combination of webscraping and API calls for our project. 

Webscraping
* Box Office Mojo

API
 * TheMovieDB.org
 * OMDB

Once we collected the data, our initial results were for 1,000 of the highest grossing movies of all time. In order to keep the data relevant, we focused on movies released between 2010-2020. This yielded us a result of 238 movies. 

# Our Recommendations

## Microsoft should utilize its existing IP and create a new Movie Saga based on the Halo Franchise.
The Halo Franchise is an exciting Microsoft IP which has expanded into a huge universe spanning beyond video games. Its cannon is featured in novels, tv shows, music, comics and more. The top grossing films of the last decade feature existing IP and match the genre Halo is based on. Creating a Halo movie Franchise is highly recommended.

## Microsoft should hire 'A-List' actors top directors.
While the budget would inevitably increase. From the Data, it is likely that a higher budget movie made by quality directors and known actors will experience longterm success.

# Conclusion

Upon reviewing of our analysis, we determined that Microsoft should create a movie saga based on Halo Franchise for the following reasons.

## 1. Highest grossing films come from existing IP franchises.
To examine the top films of the decade we filtered the top 25 movies of the decade by films with the highest adjusted lifetime 

Further filtering our data, we created a list of the top 25 movies of the decade, 24/25 of these films stemmed from existing IPs in video games, television, movies, or books. The only outlier was Disney's "Frozen" which is loosely based on the 1845 novel, "Snow Queen" by Hans Christian Andersen. Our conclusion is that, by utilizing existing IP's, you can increase liklihood of a film having a higher gross revenue over its lifetime.


[Insert Pie Char Here]
![Pie Chart](/images/pie_chart_og_ip.png)
We used a simple pie chart to emphasize this statistic.

## 2. Highest lifetime gross  Genres Action, Adventure, Sci-Fi.

We wanted to find out what the popular genres in the movie industry are today. By comparing the descriptive statistics of each of the genres, plotted over Adjusted Lifetime Gross, we were able to see that the three franchises with the highest gross were Action, Adventure, and Sci-Fi

[Insert Boxplot]

## 3. Hiring accomplished Actors and Directors has a positive trend on Gross Income.
While the relationship between big name actors, top directors and high grossing films might seem commensense, we present statistical evidence that demonstrates there is a positive relationship between the two. 

* Interesting insight, while the top grossing movies were directed by men, recent data from TMDB points that the average popular director is female
[Insert Bar graphs]


# Next Steps

* Look at Budget per genre
* Duration of movies compared to Adj. Lifetime Gross
* Compare creating your own films to leasing existing IP out 
* Success rate of sequels