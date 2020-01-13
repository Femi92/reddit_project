# Reddit: r/MCFC vs r/RedDevils
## Subreddit Classification with Natural Language Processing

### Problem Statement:


Despite the historical success of Manchester United over the years, their recent decline along with the subsequent rise of rivals of Manchester City has put their status as the number 1 team in Manchester under severe threat. This risks the club losing a generation of fans in their own city to their neighbors. Ultimately, my goal is to discover whether their 

### Web Scraping

In order to get a better understanding on how the NLP tools worked, I decided to use two subreddits from soccer teams I closely follow. I chose the following two subreddits r/MCFC and r/RedDevils since this is where the fans of the two teams conglomerate on the website.

I did a separate notebooks for each subreddit where I scraped the data using a function that pulled the posts and comments, and saved each results in a .csv dataframe. Subsequently, I converged the two subreddits into one dataframe in a third notebook and into a new .csv. 


### EDA

The initial EDA was to see if any posts had any nulls that needed to be taken care of. Roughly 65% of the initial data pull had photos/gifs etc. that were marked down as nulls in the dataframe. I felt the best decision at the time was to delete the rows that had displayed nulls in the post column. Ultimately I was still left with 1,371 posts which was sufficient to complete this analysis. 

### Data Cleaning

The next step was to clean the data I had gathered from the reddit scrapes to prepare it for analysis. 


