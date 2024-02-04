# Data-Science-subreddits
Collecting posts and top 3 comments in the data science subreddit

Those new to the data science field, might want to find out what real practitioners and soon-to-be data scientists are concerned about. One place where you may find such information is X (formerly known as Twitter). However, X users often use their real identities and may have reservations about sharing all their opinions publicly. Another place where such information maybe found is the datascience subreddit on Reddit.com (https://www.reddit.com/r/datascience/). Users are assumed to be anonymous and they are more likely to share their opinions without reservations. To find out common concerns among the datascience subreddit users, it might be a good idea to collect the top 100 posts in the subreddit in the year 2023. You might also collect the top 3 comments of each of those posts. 

The posts collected suffice the following conditions:
-posts are only from the year 2023
-the integer time format converted into year-month-day
-only posts with scores more than 50 were considered
-only post titles with more than 5 words were kept
-minimum 100 posts were collected
-three comments collected for each post

The PRAW package was leveaged to achieve the same.

The results are stored in a csv file having the following columns:

Column 1: Date

Column 2: Post score

Column 3: Post title

Column 4: Top comment 1

Column 5: Top comment 2

Column 6: Top comment 3
