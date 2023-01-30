# Ikman.lk Car Price Extractor

Python script is used to extract car advertisements information such as price, year of manufacture (YoM), mileage, and district from the 'cars' section of the website ikman.lk. The user can search using keywords (model) and limit the output by specifying the number of pages displayed and minimum YoM.

## Requirements
- Requests (pip install requests)
- BeautifulSoup (pip install beautifulsoup4)
- Pandas (pip install pandas)

## Usage
- Run the script in a terminal or command prompt.
- Enter the car model name (e.g. Lancer EX)
- Enter the minimum year of manufacture desired
- Enter the number of pages to extract information from
- The extracted information will be displayed as a Pandas DataFrame

## Inputs
The script will prompt the user for the following inputs:

- Car Model: Keyword to search for cars on ikman.lk
- Minimum YoM: Minimum year of manufacture to be considered for search results
- Pages to Extract: Number of pages of search results to be displayed

## Results
After the user has entered the required information, the script will extract the required information from the website and store it in a pandas dataframe. The information stored in the dataframe includes the price, YoM, mileage, and district of the advertisement.

The information stored in the dataframe can be used for further analysis. For example, you can find the average price of a car based on its YoM, or find the average mileage of a car based on its district.

## Conclusion
This script can be used as a starting point for anyone looking to analyze car advertisements on the ikman.lk website. By providing information such as the price, YoM, mileage, and district of the advertisement, this script can help you make informed decisions when buying a car. Further multiple filters can be accomodated by changing the script to improve the output quality.

## Sources
Code optimization done with OpenAI
