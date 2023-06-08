# Bookstore Web scraping

This is a Pyhton based web scraping project for machine learning portfolio. This project is associated with https://books.toscrape.com/ website which is specially design for training web scraping.

In this project I have built a mechanism to collect information about every book in the website, scraping through pagination.

Finally, I have made some conclusions about the data I have collected, using graphical representations like charts and graphs.


## Installation

There are two main libraries that I have used for this project.
- [Requests](https://requests.readthedocs.io/en/latest/)
- [BeutifulSoup4](https://beautiful-soup-4.readthedocs.io/en/latest) 

```bash
  # this will install 'requests' library
  !pip install requests

  # this command will install BeutifulSoup4
  !pip install bs4
```
## 🏆 Lessons Learned

1. Usage of *Requests* library to extract text content from a webpage.
2. Usage of *BeautifulSoup4* library to filter-out the data we need from html/xml content.
3. Preparing a *DataFrame* using extracted data from webpage
4. Deriving some conclusions from scraped data
