# Banking ETL Pipeline

## About the Project
This project extracts banking data from Wikipedia, transforms bank asset values into different currencies using exchange rates from a CSV file, and loads the cleaned data into both a CSV file and Microsoft SQL Server.

## ETL Workflow
1. **Extract:** Fetches the list of the world's largest banks from Wikipedia.
2. **Transform:** Cleans the asset values and converts them into PKR, INR, EUR, and GBP.
3. **Load:** Saves the transformed data to a CSV file and a Microsoft SQL Server table.

## Project Structure
- `INPUT/Book1.csv` – Currency exchange rates.
- `OUTPUT/cleaned_data.csv` – Transformed banking data.
- `LOG/code_log.txt` – Pipeline execution logs.
- `code_file.ipynb` – Python ETL implementation.
- `architecture.png` – Pipeline architecture diagram.

## Technologies Used
Python, Pandas, BeautifulSoup, Requests, SQLAlchemy, Microsoft SQL Server, and CSV.

## Key Features
- Web scraping using BeautifulSoup.
- Data cleaning and currency conversion.
- Automated logging.
- Dual data loading into CSV and Microsoft SQL Server.

## How to Run
Install the required Python libraries, configure the SQL Server connection, and run the notebook. Make sure the input exchange-rate CSV file and target database are available.
