# Job Scraper and Requirement Analyzer

This project involves scraping job listings from Indeed based on user input for job keywords. The scraper retrieves job positions, company names, locations, job state dates, and requirements. The data is then saved to an Excel file. Additionally, the project includes text analysis on the 'Requirement' column to identify the most frequent words. This involves cleaning and tokenizing the text, removing stop words and additional common words, and counting word frequencies.

## Key Features:
- **Web Scraping:** Used Selenium to navigate and interact with the Indeed website, including entering job keywords and navigating through search results.
- **Data Extraction:** Collected job position titles, company names, job locations, state dates, and job requirements from the search results.
- **Excel Export:** Saved the extracted data into an Excel file for further analysis.
- **Text Analysis:** Cleaned and tokenized the 'Requirement' column to identify the most frequent words using NLTK and pandas.

## Key Skills:
- **Programming:** Python (Selenium, pandas, NLTK)
- **Web Scraping:** Navigating websites, interacting with web elements, handling dynamic content
- **Data Extraction:** Data collection and organization from web sources
- **Text Analysis:** Tokenization, stop word removal, frequency analysis

## Python Libraries:
- **Selenium** (`from selenium import webdriver`)
  - For automating web browser interactions
  - **By** (`from selenium.webdriver.common.by import By`)
    - For locating elements on a web page
  - **WebDriverWait** (`from selenium.webdriver.support.ui import WebDriverWait`)
    - For implementing explicit waits in Selenium to pause execution until a condition is met
  - **Expected Conditions** (`from selenium.webdriver.support import expected_conditions as EC`)
    - For specifying conditions to be met before proceeding in Selenium scripts
- **Pandas** (`import pandas as pd`)
  - For reading, manipulating, and analyzing data
- **Collections** (`from collections import Counter`)
  - For counting hashable objects, commonly used for counting occurrences of elements in a list
- **NLTK** (`from nltk.corpus import stopwords`)
  - For working with natural language processing tasks, specifically for retrieving stop words
- **Regular Expressions** (`import re`)
  - For performing pattern matching and text processing tasks

---------------------------

<img width="1003" alt="image" src="https://github.com/user-attachments/assets/519fd6d5-460c-458a-90e8-740155323c24">
<img width="477" alt="image" src="https://github.com/user-attachments/assets/e0e659a5-0f93-47e3-9587-f87181c0727d">
