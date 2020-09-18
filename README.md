# stockExtractor
Using python to web-scrape real-time stock data.

Using Python we can use web-scraping to find live stock data. Live share prices are difficult to find without paying a cost and most websites displaying 'live' stock data is actually 15 minutes late! Something must be done!

The funtion I have created contains a dictionary including possible stocks you want to find. The first parameter is the country, e.g. UK, the second is the stock code e.g. LLOY and the third is the time between each ping.  

The scraper works from investing.com, so any investing.com link will work provided it is in the same format (which they are), however with adjustment any website will work.

Note in order to extract the information we must 'disguise' ourselves as a browser,in this case Chrome. In the future we could change this with every ping. 

Do realise the fact that many modern websites have defences to tackly web-scraping such as IP banning which could be bypassed using a VPN, which I have not implimented. 

*required modules: time, bs4*
