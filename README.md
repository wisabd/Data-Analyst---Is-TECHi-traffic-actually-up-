# Data-Analyst---Is-TECHi-traffic-actually-up-
Project


<img width="1277" height="315" alt="image" src="https://github.com/user-attachments/assets/fd7e0a56-91ca-4747-9a65-3140726bae9c" />

<img width="1197" height="752" alt="image" src="https://github.com/user-attachments/assets/3e1d2c45-0ae6-4fd7-9dc2-254814346761" />


<img width="1507" height="690" alt="image" src="https://github.com/user-attachments/assets/abc0d31f-badb-4bc9-98b1-4a4663c703a0" />

<img width="1062" height="615" alt="image" src="https://github.com/user-attachments/assets/ee793933-a07f-47e7-879a-21cbca816d50" />




This is a project to scrape the first 20 articles from each section of the Techi website.

Requirements:
- Python 3.10
- Selenium
- BeautifulSoup
- Pandas
- Requests
- JSON
- Gazetteer

Files:
- company_gazetteer.json : contains the list of company names
- techi_articles.csv : contains the scraped articles
- gazetteer.py : contains the code to scrape the articles
- README.md


How to run the code:
- Download the code from the repository and save all files in a folder
- Run the techi_first_article.ipynb file to scrape the articles, and build techi_articles.csv on your own.
- Gazetter.py is run from within the jupyter notebook to load check if article contains a company name. 
- Run the techi_articles.csv file to save the articles

Main decisions:
- Used Selenium to scrape the articles because it is a dynamic website and the articles are loaded dynamically as you scroll down the page.
- Split the article format into 3 categories: news/analysis, forecast, and comparison.
- Implemented Gazetteer.py to check if the article contains a company name, it performs better than SpaCy.
     - Used SP500 to check whether company name is there in title or not

