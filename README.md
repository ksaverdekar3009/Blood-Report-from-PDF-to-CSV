# Blood Report PDF to CSV Converter

Project Description:
This project is designed to automate the extraction of diagnostic test results from blood report PDFs and convert the data into a structured CSV format. By utilizing Python's libraries such as pdfplumber, re (Regular Expressions), and pandas, the program identifies and parses test details such as the test name, result values, units, and reference intervals from the text in the PDF. The extracted data is then mapped into a tabular format and saved as a CSV file for easier analysis and integration with other data systems.

Key Features:
PDF Parsing:
Extracts text data from specified pages of a PDF blood report.

Regex-based Data Extraction:
Employs regular expressions to identify and parse relevant fields like:
Test Name
Status (Normal, High, Low)
Value
Unit
Biological Reference Interval

Data Mapping and Validation:
Captures extracted data as structured dictionaries for streamlined processing.
Handles non-standard or missing data gracefully.

CSV Output:
Converts the processed data into a clean and readable CSV file for storage and further use.

Usage:
Input the path of the blood report PDF file.
Run the script to extract, validate, and structure the data.
The results are stored in a CSV file, ready for data analysis or reporting.
This tool is especially useful for healthcare professionals, researchers, and data analysts working with large volumes of diagnostic data.
