# A WebScraping Tool to scrape top Github repositories for different Topics
Description of Project: 
- Web scraping refers to the extraction of data from a website. This information is collected and then exported into a format that is more useful for the user. Be it a spreadsheet or an API.
- I scraped https://github.com/topics. I got a list of topics and for every topic I got the the topic title, topic page URL and topic description. For each topic, I got the top 30 repositories in the topic from the topic page. For each repository I used the repo name, username, stars and repo URL. Then I created a CSV file for each repository in the following format: Repo Name, Username, Stars, Repo URL
- I used the following tools: Python, Beautiful Soup, requests, and Pandas to create the project


PS: I only added the first 5 csv files for the scraped data in the repository
