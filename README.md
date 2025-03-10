# Web-Scraping-Job-Market

This project automates the extraction of job-related data from Jooble using web scraping techniques. It collects company details such as name, headquarters, industry, size, website, location, and year of foundation, processes the extracted data, and exports it as an Excel file for further analysis.

🚀 Features

Automated Web Scraping: Uses Requests-HTML and BeautifulSoup to scrape job listings.

Data Cleaning & Processing: Handles missing values, refines text formats, and normalizes extracted data.

Dynamic Content Handling: Implements headless browser rendering for JavaScript-heavy pages.

Automated Data Export: Converts extracted data into a Pandas DataFrame and exports it as a timestamped Excel file.

Error Handling & Scalability: Includes retries, exception handling, and structured storage for seamless operation.

🛠️ Technologies Used

Python,
Requests-HTML & BeautifulSoup (for web scraping),
Pandas (for data processing & storage),
OS & Time Modules (for automation & file handling)
Excel File Export (openpyxl),
