# ikman.lk Car Ad Scraper

This script is a simple web scraper that scrapes car ads from the website ikman.lk. The user can choose to filter the results by car model, minimum/maximum year of manufacture, minimum/maximum price, minimum/maximum mileage, and number of pages to scrape. The results are stored in a Pandas DataFrame and visualized using Plotly.

## Requirements
- BeautifulSoup
- requests
- pandas
- urllib.parse
- tkinter
- plotly.express

## Usage
 1. Clone the repository and navigate to the directory in the terminal.
 2. Run the script using the following command:
 ```
 python ikman_scraper.py
 ```
 3. A GUI window will appear where you can enter the desired filters. Fill out the form and click submit.
 4. The program will scrape the specified number of pages, store the results in a Pandas DataFrame, and visualize the data using Plotly.

## Customization

The user can choose to modify the data analysis, data visualization, and the GUI window as needed. The code is not commented yet therefore some understanding on python is required to do any modifications for the moment.

## Sources
Code optimization and plotting done using OpenAI
