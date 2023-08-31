# CarNumber
## CarNumberAuctionPlate.ipynb
### Overview
The CarNumberAuctionPlate.ipynb notebook contains Python code for scraping and analyzing auction plate data for different vehicle registration stations using web scraping. The script retrieves data from the Taiwan Motor Vehicle Driver Information Service (MVDis) website, analyzes the car numbers and prices, calculates the sum of the last four digits of each car number, and determines if each car number is a lucky number based on a predefined lucky number DataFrame. The results are then saved to Excel files for each station.

### Usage
1. Open the CarNumberAuctionPlate.ipynb notebook using Jupyter Notebook or Jupyter Lab.

2. Make sure you have installed the required Python packages listed in the notebook's code.

3. Run each code cell in the notebook to execute the corresponding functions.

4. The scraped and analyzed data will be saved to the ./result directory in Excel files named Bidding_{stationCode}.xlsx and Auction_Records_{stationCode}.xlsx.

## CarNumberFatefulPlate.ipynb
### Overview
The CarNumberFatefulPlate.ipynb notebook contains Python code for scraping and analyzing lucky numbers data using web scraping. The script sends post requests with different numbers to a specific website to scrape lucky numbers data. It then analyzes the data and filters out unlucky numbers based on predefined criteria. The filtered lucky numbers are merged with a DataFrame containing additional information. The results are saved to an Excel file.

## Usage
1. Open the CarNumberFatefulPlate.ipynb notebook using Jupyter Notebook or Jupyter Lab.

2. Make sure you have installed the required Python packages listed in the notebook's code.

3. Run each code cell in the notebook to execute the corresponding functions.

4. The scraped, analyzed, and merged data will be saved to the ./result directory in an Excel file named lucky_number_best.xlsx.
