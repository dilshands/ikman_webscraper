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
1. Clone or download the repository to your local machine
2. Open the 'ikman.lk_carinfo_scraper_v2.ipynb' Jupyter Notebook file in your local machine
3. Install the required packages specified in the first code cell of the notebook
4. Run all cells in the notebook in sequence to scrape the car information

## Customization

The user can choose to modify the data analysis, data visualization, and the GUI window as needed. The code is not commented yet therefore some understanding on python is required to do any modifications for the moment.

## Sources
Code optimization and plotting done using OpenAI

## Versions
##### V1 
Filters: model/ minimum year of manufacture/ number of pages to go through
Output: Dataframe with year/price/mileage/district/link of the filtered results

##### V2
Filters: model/ minimum year of manufacture/ maximum year of manufacture/ minimum mileage/ maximum mileage/ minimum price/ maximum price/ number of pages to go through
Output: Scatterplot of price vs. mileage grouped by year of manufacture. Added the URL of the advertisement as a label
