# Web-Scraping-using-Python-Multiple-Pages
This python script will scrape all the articles of a news websites and the number of pages that the script will scrape can be modified. In this script, we have set the range value to 3, thus it will scrape up to page 2 of the news website. 

1. First, It  will take the url and the number of pages it will scrape. 
2. It will then load the first page and then scrape the list of article's link.
3. It will now go thru all the link and scrape for the author,date,title and body of the article
4. It will get all the body of text under the 'p' tag. It also removes text advertisements which are children of the 'p' 
tag thus I used the decompose python method
5. Lastly, It will save the scraped data to a csv
6. Steps 2 to 5 will be performed on all the pages
