# Highest Earning Companies in the USA

- Developed a web scraping project to extract and structure data from a Wikipedia page using BeautifulSoup, Requests, and Pandas libraries.

- Targeted the "List of largest companies in the United States by revenue" table, containing data such as company name, rank, industry, revenue, and more.

- Utilized BeautifulSoup to parse the HTML structure of the web page and identify the desired table through class-based filtering and indexing, resolving issues caused by multiple tables.

- Extracted table headers (rank, name, industry, etc.) using the <th> tags and cleaned the data with Python's .strip() method for consistent formatting.

- Parsed rows of data (<tr> tags) and their respective columns (<td> tags) to create structured lists, ensuring accurate alignment of data elements.

- Constructed a Pandas DataFrame to organize the extracted data efficiently, facilitating further analysis or manipulation.

- Exported the structured data to a CSV file using pandas.to_csv() for easy integration into external tools or dashboards.

- Implemented error handling and debugged issues related to inconsistent tags and empty rows, ensuring a smooth and reliable data extraction process.

- Demonstrated how to automate repetitive data collection tasks, showcasing proficiency in web scraping and data engineering principles.

- Encouraged scalability by leaving the solution adaptable for other web tables or similar datasets.
