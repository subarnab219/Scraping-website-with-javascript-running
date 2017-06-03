# Scraping-website-with-javascript-running
Many a time we see there are inherent structure in the website. However, soup do not contain all the HTML tags. The reason could be either your parser is not working properly or there is javascript running in the website. 
Solution for 1st prob is to switch the parser:
1. "lxml" to "html-parser"
2. "html5" to "html-parser"


If a java script running in the website, one option is to scrape using Selenium. Refer to .pynb file for code. 

Download geckodriver. Read http://selenium-python.readthedocs.io/
