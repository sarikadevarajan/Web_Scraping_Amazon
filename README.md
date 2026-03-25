# Web_Scraping_Amazon
This project is a Python-based web scraper designed to collect and analyze laptop product data from Amazon. It uses the requests library to fetch webpage content and BeautifulSoup to parse HTML elements and extract relevant product information.

The scraper gathers detailed attributes for each laptop, including title, price, brand, RAM, processor type, storage capacity, operating system, color, and customer ratings. Regular expressions are used extensively to clean and accurately extract structured data such as RAM size, SSD capacity, processor details (Intel, AMD, Apple, etc.), and Windows versions from unstructured product titles.

The extracted data is stored in a list of dictionaries and then converted into a Pandas DataFrame for further analysis and visualization. This makes it easy to explore trends such as popular brands, common configurations, and price distributions.

The project demonstrates key data science and engineering concepts such as web scraping, data cleaning, feature extraction, and structured data handling. It is particularly useful for beginners looking to understand how raw web data can be transformed into meaningful insights.
