# Forex Factory Calendar Scraper

This script scrapes event data from the Forex Factory calendar for a specified date range and saves it to a CSV file. It's handy for anyone wanting to automate data collection for Forex events.

## How to Use

1. Clone or download this repository.
2. Install the required libraries by running:

   ```bash
   pip install selenium webdriver-manager beautifulsoup4  
   ```

   *(If you're using Python below 3.9, also run `pip install tzdata`.)*
3. Edit the `START_DATE` and `END_DATE` in the script to set your desired date range.
4. Run the script:

   ```bash
   python forex_scraper.py  
   ```

The scraped data will be saved in a file named `forex_factory_calendar.csv` in the same folder.

## Requirements

* Python 3.9 or higher
* Google Chrome installed
* Stable internet connection

Feel free to tweak the code as needed. If you face any issues, let me know!
