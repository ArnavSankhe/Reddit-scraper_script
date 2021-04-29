# Reddit-scraper_script
Recently wsb have been very popular in news with their un imaginary achievement in stock market, big hedge funds are already aware of power that reddit holds. This scraper script is to get data from reddit and analyse however you want.

# Description
This script is use to scrape reddit database. I have scraped data from r/jokes subreddit and created a database of jokes where they are divided as title, body, scores i.e. upvotes. we can also get other data like number of downvotes, number of comments and urls of those posts. I have not posted my analysis which is to find humor score using nlp as its part of personal project.
Here i have shown how we can use pandas dataframe to easily transfer all data to excel.

#  How to Start
1) First visite the site : https://old.reddit.com/prefs/apps/
2) Then click on create app
3) then enter name(*it can ne anything as it dosent matter)
4) Select script and then in redirect url type : http://localhost:8080 and click on create app.
5) then you will get client id and its secret just replace those and the subreddit name in original script that you wanto scrape.
