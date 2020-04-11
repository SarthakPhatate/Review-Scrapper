# Review-Scrapper
Web Scraping(Text)

## Introduction:
Web scraping is a technique using which the webpages from the internet are fetched and parsed to understand and extract specific information similar to a human being. Web scrapping consists of two parts:
•	Web Crawling Accessing the webpages over the internet and pulling data from them.
•	HTML Parsing Parsing the HTML content of the webpages obtained through web crawling and then extracting specific information from it.
Hence, web scrappers are applications/bots, which automatically send requests to websites and then extract the desired information from the website output.
Let’s take an example: 
how do we buy a phone online?
1.	We first look for a phone with good reviews
2.	We see on which website it’s available at the lowest price
3.	We check whether it’s  delivered in our area or not
4.	If everything looks good, then we buy the phone.
What if there is a computer program that can do all of these for us? That’s what web scrappers necessarily do. They try to understand the webpage content as a human would do.

In this project, we’ll take the example of buying a phone online further and try to scrap the reviews from the website about the phone that we are planning to buy.

## Prerequisites:
The important modules needed for this projects are flask and beautifulSoup and sore other are given in requirements.txt file ,to install all dependencies just run :pip install -r requirements.txt

For hosting the website I have used Heroku cloud as it gives first 5 app hosting free
## Heroku:
The Python app that we have developed is residing on our local machine. But to make it available to end-users,  we need to deploy it to either an on-premise server or to a cloud service. Heroku is one such cloud service provider. It is free to use(till 5 applications).
We’ll deploy this application to the Heroku cloud, and then anybody with the URL can then consume our app.

The website will look as follows
Search Page of the website

![Search Page of the website](https://github.com/SarthakPhatate/Review-Scrapper/blob/master/SearchPage.png)

Review Page of the website

![Review Page of the website](https://github.com/SarthakPhatate/Review-Scrapper/blob/master/ReviewPage.png)
