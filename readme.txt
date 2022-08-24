This program will scrape listings from https://capitalcityonlineauction.com/Public/Auction and place them in one spreadsheet. Unfortunately the urls on the site can vary widely
and the person listing might not post everything correctly so there is a chance it might not run. I have attempted to handle those errors and omit the information if it is not
available. To change the number of autions to scrape, simply change the "scrape" variable at the top located under "driver = webdriver.Chrome()". It can take up to an hour to run
when scraping 10+ auctions since each one has 75-250 listings. 
