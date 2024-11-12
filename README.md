# Web Scraping with BeautifulSoup and Requests: Extract text and links from web pages

## Created by:
**Khaled Ashraf**  
AI Engineer

## Purpose:
This Jupyter Notebook demonstrates web scraping techniques using the `requests` and `BeautifulSoup` libraries. The notebook is divided into three sections:
1. Extracting text content from a Wikipedia page (Arabic).
2. Extracting links from dynamically generated URLs.
3. Extracting text content from a specific webpage, in this case, the Wikipedia page for Zamalek Club.

## Libraries Used:
- **requests**: Used to make HTTP requests to fetch webpage content.
- **BeautifulSoup** (from `bs4`): Used to parse HTML content and extract specific elements like text and links.

## Steps:
### 1. Extracting Text from a Wikipedia Page (Arabic)
This section demonstrates how to fetch content from the Wikipedia page for "Nadi El Zamalek" (Arabic), extract the text, and save it as a plain text file.

### 2. Extracting Links from Dynamically Generated URLs
In this section, URLs are dynamically constructed from a predefined list (`T`), and the script extracts all the hyperlinks (`<a>` tags) from each page.

### 3. Combining Both Extracting Text and Links
This section combines the previous two techniques, allowing you to extract both plain text and links from different pages in the same notebook.

## Output:
- The first part of the notebook will generate a file named `Zamalek_Club.txt` containing the extracted text from the Wikipedia page.
- The second part will print a list of all the links (`<a>` tags) found on the dynamically generated pages.

## Notes:
- You can customize the list `T` to scrape different pages.
- This notebook demonstrates two types of scraping: extracting plain text from a webpage and extracting links from a list of pages.
