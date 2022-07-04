# Web_Scrapping_Github_Repositories
Web Scraping Github website using  Beautiful Soup and Python
Web scraping is the process of extracting and parsing data from websites in an automated fashion using a computer program.
It’s a useful technique for creating datasets for research and learning. 
In this workshop, we’ll use Python and its ecosystem of libraries to scrape information from a website and create a dataset of CSV file(s).

Here are the steps we’ll follow to build a web scraping project from scratch:
✅ Pick a website and identify the information to be scraped into a CSV file
💾 Use the requests library to download web pages from the site programmatically
💬 Use Beautiful Soup to parse and extract information from web pages
📝 Create well-formatted CSV file(s) with the extracted information



#### Project Outline

- We're going to scrape https://github.com/topics
- We'll get a list of topics. For each topic, we'll get topic title, topic page URL and topic description
- For each topic, we'll get the top 25 repositories in the topic from the topic page
- For each repository, we'll grab the repo name, username, stars and repo URL
- For each topic we'll create a CSV file in the following format:

Repo Name,Username,Stars,Repo URL
three.js,mrdoob,69700,https://github.com/mrdoob/three.js
libgdx,libgdx,18300,https://github.com/libgdx/libgdx
