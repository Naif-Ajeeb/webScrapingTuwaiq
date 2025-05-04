# Web Scraping Project

This project scrapes book data from the [Books to Scrape](https://books.toscrape.com/) website. It collects information about books, including their titles, prices, stock availability, ratings, and descriptions, and saves the data into a CSV file for further analysis and visualization.

## Features
- Scrapes book data from multiple pages.
- Extracts details such as title, price, stock availability, rating, and description.
- Saves the data into a CSV file (`Scraped_data.csv`).
- Provides basic visualizations using Seaborn.

## Requirements
The project requires the following Python packages:
- `pandas`
- `beautifulsoup4`
- `requests`
- `seaborn`

Install the dependencies using:
```bash
pip install -r requirements.txt
```

## How to Run
1. Clone this repository or download the project files.
2. Ensure you have Python installed on your system.
3. Install the required packages using the command above.
4. Run the Jupyter Notebook (`webScraping.ipynb`) to scrape the data and generate the CSV file.

## Output
- A CSV file named `Scraped_data.csv` containing the scraped book data.
- Visualizations of book ratings and prices.

## Notes
- Ensure you have an active internet connection while running the notebook.
- The scraping process may take some time depending on the number of pages and books.

## License
This project is for educational purposes only. Please ensure compliance with the website's terms of service when scraping data.