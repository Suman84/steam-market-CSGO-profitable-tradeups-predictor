# steam-market-CSGO-profitable-tradeups-predictor

## Uses beautifulSoup for data scraping.
## predicts profitable tradeups for csgo skins.(cant when skins have wear range other than 0-1) making this predictor not very useful)

### All calculation might not always be correct, but should be good enough to point in right direction. 
### Run Predictor_using_existing_data_in_file.py to see how it works. 
### For latest data, delete everything inside skin_prices.txt and run names_and_prices_extractor_and_store_in_txtfile.py

# steps to run:
### 1. Install python 

### 2. Install required libraries with the following: only needed for extraction.
pip install beautifulsoup4 

pip install requests 

### 3.Delete old skin_prices.txt 

### 4.Run names_and_prices_extractor_and_store_in_txtfile.py. Output will be stored in a txt file.

## DISCLAIMER: This project is for educational purpose only and was developed during my time learning python.
### I used my knowlegde of maths on how trade up works in csgo, which wasn't totally correct, hence, skins with different float range from 0-1 will have bad predictions. 
### Lastly, steam blocks any user from making too many requests in short interval of time,so program will wait periodically, hence, extraction will take a lot of time. 


