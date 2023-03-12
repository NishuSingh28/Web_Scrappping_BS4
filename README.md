# Web_Scrappping_BS4

Web scraping is a technique of extracting data from web pages. Beautiful Soup is a Python library that makes it easy to scrape information from web pages. Here's an overview of how to use Beautiful Soup for web scraping:

Install Beautiful Soup: You can install Beautiful Soup using pip, a package manager for Python. Open your command prompt or terminal and run the following command:

```pip install beautifulsoup4```

Import Beautiful Soup: Once Beautiful Soup is installed, you can import it in your Python code using the following line:

```from bs4 import BeautifulSoup```

Get the HTML content: To scrape data from a web page, you first need to download its HTML content. You can use the requests library to send an HTTP request to the website and get its content.

```
import requests

url = 'https://www.example.com'
response = requests.get(url)
content = response.content 

```
Parse the HTML content: Once you have the HTML content, you can use Beautiful Soup to parse it and extract the data you need.
