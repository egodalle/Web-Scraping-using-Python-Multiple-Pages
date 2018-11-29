# Web-Scraping-using-Python-Multiple-Pages
This python script will scrape all the articles of a news websites and the number of pages that the script will scrape can be modified. In this script, we have set the page number to 3. The script will do the following:

1. First, It  will take the url and the number of pages it will scrape and then convert it to BeautifulSoup object
2. It will then scrape for the author,date and title of the article and save it to a list
3. It will get all the body of text under the 'p' tag. It also removes text advertisements which are children of the 'p' 
tag thus I used the decompose python method
4. Lastly, It will save the scraped data to a csv
