# IMDB Web Scraping of Reviews for "Munjya" Movie

## Overview

This project involves web scraping reviews from IMDB for the movie "Munjya." The objective is to extract user reviews and analyze them for insights such as sentiment analysis, common themes, and overall viewer reception.

## Getting Started

### Prerequisites

To run this project, you need to have Python 3.x installed on your machine. Additionally, you'll need to install the required libraries listed in `requirements.txt`.

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Milan-pixel-star/IMDB-Web-Scraping-of-Revies-of-Munjya-Movie.git
   ```

2. Navigate to the project directory:

   ```bash
   cd IMDB-Web-Scraping-of-Revies-of-Munjya-Movie
   ```

3. Create a virtual environment and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. **Scraping Reviews**: To scrape the reviews from IMDB, run the script `scrape_reviews.py` located in the `scripts/` directory. This script will save the reviews in a CSV file in the `data/` directory.

   ```bash
   python scripts/scrape_reviews.py
   ```

2. **Analyzing Reviews**: Use the Jupyter notebooks in the `notebooks/` directory to explore and analyze the scraped reviews. For instance, you can perform sentiment analysis or visualize the data.

   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```

## Contributing

Contributions are welcome! If you have any improvements or suggestions, feel free to create a pull request or open an issue.

### To Contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.


Feel free to reach out if you have any questions or need further assistance. Happy coding!
