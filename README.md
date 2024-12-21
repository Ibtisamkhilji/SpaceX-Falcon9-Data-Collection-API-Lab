# SpaceX Falcon 9 Data Collection API Lab

This repository contains the first lab of the SpaceX Falcon 9 Data Science Capstone Project. In this lab, we collect and preprocess data from SpaceX's API and a Wikipedia page to build a foundation for predicting Falcon 9 first-stage landing success.

## Objectives
- Learn how to interact with SpaceX's RESTful API.
- Use Python to send GET requests and retrieve rocket launch data.
- Process and parse JSON responses into a Pandas DataFrame.
- Perform web scraping to gather historical Falcon 9 launch data from Wikipedia.

## Data Sources
1. **SpaceX API**: Provides detailed information on Falcon 9 rocket launches.
   - URL: `https://api.spacexdata.com/v4/launches`
2. **Wikipedia**: Used to scrape historical launch data from the page titled "List of Falcon 9 and Falcon Heavy launches."

## Key Steps
1. **API Data Collection**:
   - Define helper functions to streamline API usage.
   - Use GET requests to retrieve JSON data from SpaceX's API.
   - Parse and convert the JSON data into a Pandas DataFrame.

2. **Web Scraping**:
   - Use `requests` and `BeautifulSoup` libraries to scrape Falcon 9 historical launch data.
   - Extract HTML table data from Wikipedia.
   - Parse and convert the table into a Pandas DataFrame.

## Requirements
Install the following Python libraries before running the code:
- `requests`
- `pandas`
- `beautifulsoup4`

You can install them using the following command:
```bash
pip install requests pandas beautifulsoup4
```

## How to Run
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the repository:
   ```bash
   cd spacex-falcon9-api-lab
   ```
3. Run the Python script for data collection:
   ```bash
   python spacex_data_collection.py
   ```

## Output
The lab generates two Pandas DataFrames:
1. Launch data retrieved from the SpaceX API.
2. Historical launch data scraped from Wikipedia.

These DataFrames can be saved as CSV files for further analysis.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- SpaceX for providing a publicly accessible API.
- Wikipedia contributors for maintaining detailed launch records.
