# Webscraping1-Web-Scraping-On-Wikipedia


We can scrap web pages using libraries such as 
  * Requests
  * beautifulsoup
  * selenium
  * scrapy
  * wikipedia for Wikipedia data
 
 
-------------------------------------------------------------------------------------------------------------
  
* BeautifulSoup --> This will retrieve or parse data from xml or html not from the page directly.

* Requests --> we cannot directly extract the info we need, it will be xml or html.
    * We use requests to get the page and beautiful soup to extract info
    * As pages have rendered javascript, requests and beautiful soup cannot do much 
    
* Selenium --> Not build for webscraping but we can configure to do web scraping
    * This will also help with the javascript pages
    * Selenium is slow
    
* Scrapy
    * Scrapy can do everything
    * We can make multiple Http requests but with other packages, it is sequential
