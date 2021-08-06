# Pyhton-Web-Scraping-from-a-Static-Website
In this notebook, we will learn how to scrape some data from a static website. A static web page is a web page that is delivered to the user's web browser exactly as stored.


#### Required Libraries:
 
 > requests -  this module allows user to send HTTP requests using Python and to get the response text.
 
 > bs4 - Beautiful Soup is a Python package for parsing HTML and XML documents. It creates parse trees that is helpful to extract the data easily.
 
 > pandas
 
#### Steps:

 > Find the URL that you want to scrape. (As per the business requirement)
 
 > Inspect the website. Select the informations that you want to scrape. (As per the business requirement)
 
 > Nevigate to the specific pages (by changing a specific word in the main url using a loop)
 
 > A request is sent to the page that is being scraped (using requests module)
 
 > The server will send the data and allows you to read the HTML or XML page from that page
 
 > Find the data you want to extract (by inspecing the page) - using bs4.BeautifulSoup module
 
 > Extract the data ( using regular expressions)
 
 > Store the data in the required format.

In this Jupyter Notebook, we are scraping news articles from  'https://www.politifact.com/'. The data includes Title, author, category, date, summary, full article and sources of the article.

Reference : https://randerson112358.medium.com/scrape-a-political-website-for-fake-real-news-using-python-b4f5b2af830b
