# Election Results Analysis

This project utilizes web scraping techniques and interactive visualizations to analyze election results. The goal is to fetch data from the [https://results.eci.gov.in/](https://results.eci.gov.in/) website, process it into a structured dataframe using Python and BeautifulSoup, and then visualize key insights using Plotly.

## Features

- **Web Scraping**: Utilizes BeautifulSoup to scrape election results data from a hypothetical website.
- **Data Processing**: Cleans and organizes the scraped data into a pandas DataFrame, converting relevant columns to numeric types.
- **Visualization**: Generates interactive visualizations including:
  - Donut chart to show seat distribution among top parties.
  - Bar chart to display the number of seats won by each party.
  - Treemap to illustrate the proportion of seats won by each party.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/adivishnu-a/Election-Results-Data-2024.git
   cd Election-Results-Data-2024
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter notebook `elec_scrape.ipynb`.
2. Run the cells to process data and generate visualizations.
3. Modify the notebook as needed.

## Requirements

- Python 3.x
- Libraries:
  - requests
  - BeautifulSoup4
  - pandas
  - plotly

## Donut Chart

![donut_chart](https://github.com/adivishnu-a/Election-Results-Data-2024/assets/95145136/858a59d3-4212-44ff-b1fd-e45be414dbb8)

## Contributing

Contributions are welcome! Fork the repository and submit a pull request with your enhancements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
