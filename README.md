
# Web Scraping with Python and BeautifulSoup

This repository contains Python scripts for web scraping data from three different websites using the BeautifulSoup library. Web scraping is a technique used to extract information from web pages by sending HTTP requests, parsing HTML content, and navigating the parse tree.

## Websites Scraped

### 1. Wikipedia

- **Description**: Wikipedia is a free online encyclopedia with articles covering a wide range of topics.
- **Scraping Approach**: The script sends an HTTP request to the Wikipedia homepage, parses the HTML content, and extracts useful information from articles.

### 2. Quotes to Scrape

- **Description**: Quotes to Scrape is a website specifically designed for practicing web scraping. It contains a collection of quotes from various authors.
- **Scraping Approach**: The script sends an HTTP request to the Quotes to Scrape website, parses the HTML content, and extracts quotes along with their authors.

### 3. Books to Scrape

- **Description**: Books to Scrape is another website designed for practicing web scraping. It contains a collection of books, including their titles, prices, ratings, and availability.
- **Scraping Approach**: The script sends an HTTP request to the Books to Scrape website, parses the HTML content, and extracts book details such as titles, prices, ratings, and availability.

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your_username/web-scraping.git
   ```

2. Navigate to the project directory:

   ```bash
   cd web-scraping
   ```

3. Run the Python scripts for scraping data from each website:

   ```bash
   python scrape_wikipedia.py
   python scrape_quotes.py
   python scrape_books.py
   ```

4. The scraped data will be saved to CSV files in the project directory.

## Dependencies

- Python 3.x
- BeautifulSoup library
- Requests library

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
