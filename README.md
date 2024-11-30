# Product Scraper

## Description
This project is a web scraper that extracts product details from an e-commerce website. It retrieves the product title and price and stores them in a structured format. The scraper uses Python with the BeautifulSoup library for parsing HTML.

## Features
- Scrapes product title and price from a specified URL.
- Handles exceptions and provides error messages for failed requests.
- Outputs product details in a dictionary format.

## Installation

### Prerequisites
- Python 3.x
- pip (Python package installer)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/shri-ui/Web_Scrape_Amazon_with_BS4.git
   cd Web_Scrape_Amazon_with_BS4
   ```

2. Create a virtual environment:
   ```bash
   python -m venv .venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     .\.venv\Scripts\Activate.ps1
     ```
   - On macOS/Linux:
     ```bash
     source .venv/bin/activate
     ```

4. Install the required libraries:
   You will need to install three Python libraries:
   - `requests`: Sends HTTP requests.
   - `beautifulsoup4`: Pulls data out of HTML and XML files.
   - `lxml`: Provides a powerful API for parsing HTML and XML.

   To install the three libraries, run the following command in your VS Code terminal:
   ```bash
   pip install requests beautifulsoup4 lxml
   ```

5. Alternatively, you can install all required packages listed in `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the scraper, execute the following command in your terminal:
```bash
python main.py
```

Make sure to update the `product_url` variable in `main.py` with the URL of the product you want to scrape.

## Output
The scraper will output the product details in the console. Here’s an example of the output:

```
Product Title: Example Product
Price: $19.99
Product URL: https://www.example.com/product
```

## Output Images
Here are some example images of the output:

![Output](images/output.jpg)

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) for HTML parsing.
- [Requests](https://docs.python-requests.org/en/master/) for making HTTP requests.
