## Flipkart_Price_Scraper
This micro project is a Python-based web scraper that extracts the prices of mobile phones listed on Flipkart, an Indian e-commerce website. It uses the Selenium and Beautiful Soup libraries to automate the web scraping process and stores the extracted data in a Pandas DataFrame. 

### Requirements
To run this project, you need to have Python 3 and the following libraries installed:

1. Selenium
2. Beautiful Soup
3. Pandas
4. ChromeDriver

You also need to have the Chrome browser installed on your system, as the project uses ChromeDriver to automate web browsing.

### Usage
To use this project, simply run the flipkart_price_scraper.py file using Python. The script will launch Chrome and navigate to the Flipkart website. It will then search for mobile phones and extract their prices. Finally, it will store the extracted data in a Pandas DataFrame and print it to the console.

By default, the project extracts the prices of the first 10 mobile phones listed on Flipkart. However, you can easily modify the script to extract more or fewer prices by changing the value of the NUM_PRODUCTS variable.

### Contributing
Contributions to this project are welcome! If you find a bug or have a suggestion for a new feature, please open an issue on GitHub.
