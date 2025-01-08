# Movie Scraper and Data Visualization

This project involves scraping movie details from a web page and visualizing the data in a tabular format. The movie details include the movie name, release year, and duration. The data is then saved as a CSV file for further use.

## Project Structure

- `Imdb_Scraping.ipynb`: Jupyter Notebook containing the scraping logic, data extraction, and visualization.
- `movies.csv`: The CSV file generated with the scraped movie data.

## Features

- Scrape movie names, release years, and durations.
- Clean and process the data into a structured format.
- Visualize the data in a well-organized table.
- Save the processed movie details as a CSV file.

## Requirements

This project is built using Jupyter Notebook and the following libraries:

- `pandas`: Data manipulation and CSV saving.
- `requests`: For fetching the webpage.
- `beautifulsoup4`: For scraping the webpage.

Note: If you are running the code in a new environment, you may need to install the required libraries using `pip install pandas requests beautifulsoup4`.

## How to Use

1. Clone or download the repository.
2. Open the `Imdb_Scraping.ipynb` file in Jupyter Notebook.
3. Run the notebook cells to scrape the movie data and visualize it.
4. The movie data will be saved as a CSV file named `movies.csv`.
