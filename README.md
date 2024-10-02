# Patterns-in-comments-from-Reddit-social-network
The objectives of this projectconcerning User/Comments in Reddit social network are to:

● Predict the gender of a user, based on their activity and comments

● Cluster the comments and analyze to which subreddit the clusters
belong

● Experiment language models

Indeed,
Reddit is an entertainment, social networking, and news website where registered community members
can submit content, such as text posts or direct links, making it essentially an online bulletin board system.
Registered users can then vote submissions up or down to organize the posts and determine their position
on the site's pages. Content entries are organized by areas of interest called "subreddits". The subreddit
topics include news, gaming, movies, music, books, fitness, food, and photosharing, among many others.
When items (links or text posts) are submitted to a subreddit, users can vote for or against them
(upvote/downvote). Each subreddit has a front page that shows newer submissions that have been rated
highly. Users can also post comments about the submission and respond back and forth in a conversation-
tree of comments; the comments themselves can also be upvoted and downvoted. The front page of the
site itself shows a combination of the highest-rated posts out of all the subreddits a user is subscribed to.
The Reddit website has an API and its code is open source. In July 2015, a Reddit user identified as
Stuck_In_the_Matrix made public a dataset of Reddit comments for research. Each data point contains
comment text, score, author, subreddit, position in comment tree and other fields that are available
through Reddit's API.
https://www.reddit.com/r/datasets/comments/3bxlg7/i_have_every_publicly_available_reddit_comment/
We selected a total of 20k users, with their 1.4 million comments. Among these, we selected 5000 with
self-reported gender for the supervised task, and the remaining 15000 for the unsupervised one. You will
be provided with 3 different csv data files:
- data_supervised.csv contains all comments of the users selected for supervised learning.
- target_supervised.csv contains the genders of the users selected for the supervised part. 1 stands
for female, 0 for male.
- data_unsupervised.csv contains the comments of the users selected for the unsupervised task.
Each comment has the following structure:
- author - contains the username of the author
- subreddit - contains the subreddit in which the comment was posted
- created_utc - contains the date of submission in unixtime format.
- body - contains the text of the comment.

  ## Section 1 – Data exploration and pre-processing
  ## Section 2 – Supervised learning – classification
  ## Section 3 – Unsupervised learning – clustering
  ## Section 4 – Language Models exploration
