# Scraping Data from Wikipedia and Creating a Dashboard

This Python script scrapes data from a Wikipedia page listing the largest companies in the United States by revenue and creates a dashboard using Pandas. Additionally, a Power BI dashboard has been created to visualize the data.

## Requirements

- Python 3.x
- BeautifulSoup
- Pandas
- Power BI Desktop (for viewing the dashboard)

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/your_username/your_repository.git
    ```

2. Install Python dependencies:

    ```
    pip install beautifulsoup4 pandas
    ```

## Usage

1. Run the Python script:

    ```
    python scrape_and_dashboard.py
    ```

2. The script will scrape the data from [Wikipedia](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue), create a Pandas DataFrame, and export the data to a CSV file named `Companies.csv`.

3. Open the Power BI dashboard (`CompaniesDashboard.pbix`) using Power BI Desktop to visualize the data.

## Files

- `scrape_and_dashboard.py`: Python script for scraping data and creating the dashboard.
- `Companies.csv`: CSV file containing the scraped data.
- `CompaniesDashboard.pbix`: Power BI dashboard file.

## Credits

- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)
- [Pandas](https://pandas.pydata.org/)
- [Power BI](https://powerbi.microsoft.com/)
