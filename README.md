# Web-Crawler-for-Hunet-Lecture-Data
Web Crawler for Hunet Lecture Data: Automates data extraction from Hunet using Selenium and BeautifulSoup. Collects lecture details and images based on user input, saving results in CSV and Excel formats. Ideal for gathering and analyzing online education content.
Features
Keyword Search: Allows users to input a keyword to search for relevant lectures on the Hunet platform.
Customizable Data Collection: Users can specify the number of lectures to retrieve.
Data Extraction: Gathers details such as lecture title, satisfaction rating, reviews, and price.
Image Download: Downloads lecture images and saves them locally.
Data Storage: Saves collected data in both CSV and Excel formats.
Excel Integration: Optionally adds lecture images to the Excel file for better visual representation.
Install Required Libraries:
Ensure you have the necessary libraries installed. You can install them using pip:

bash
Copy code
pip install selenium beautifulsoup4 pandas openpyxl
Download WebDriver:
Download the appropriate Chrome WebDriver for your operating system from ChromeDriver. Update the path to the WebDriver in the script.

Run the Script:
Execute the script. You'll be prompted to provide:

A keyword for the lecture search.
The number of lectures you want to collect (default is 10).
The folder path where the files will be saved (default is c:\py_temp\).
Output:

Lecture data will be saved in both CSV and Excel formats.
Images of lectures will be saved in a designated folder.
An Excel file with images (if applicable) will be created.
Code Overview
Libraries Imported: Selenium, BeautifulSoup, pandas, openpyxl, and others.
User Input: Prompts for keyword, lecture count, and folder path.
Data Collection:
Opens the Hunet website and performs a search.
Clicks to load more pages if necessary.
Extracts lecture details and images.
Data Storage:
Saves lecture data to CSV and Excel files.
Optionally includes images in the Excel file.
Dependencies
Python 3.x
Chrome WebDriver
Selenium
BeautifulSoup4
pandas
openpyxl
