# Voter ID Extraction

This project focuses on extracting voter ID data from PDF documents. The extracted data can be used for analysis, verification, or other purposes. The project utilizes Python libraries like EacyOCR, PIL, and ImageIO for accurate data extraction. The extracted data is stored in a SQL Server database using SQLAlchemy and PyMySQL for efficient data storage and retrieval.

## Prerequisites

Make sure you have the following installed:

- Python 3.x
- EacyOCR library
- PIL (Python Imaging Library)
- ImageIO library
- SQL Server
- SQLAlchemy
- PyMySQL

## Getting Started

1. Clone this repository to your local machine.
2. Install the required Python libraries mentioned in the prerequisites.
3. Set up your SQL Server database and configure the necessary credentials.
4. Update the configuration file (`config.py`) with the appropriate database connection details.
5. Prepare the PDF documents containing voter ID data for extraction and place them in the designated input folder.
6. Run the `voter_id_extraction.py` script to extract the data and store it in the database.
7. Access the extracted data from the database for further analysis or processing.

## Usage

1. Place the PDF documents with voter ID data in the `input` folder.
2. Run the `voter_id_extraction.py` script using the command: `python voter_id_extraction.py`.
3. The script will extract the data from the PDFs and store it in the configured SQL Server database.
4. Access the extracted data from the database using SQL queries or integrate it with other applications as required.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments

- [EacyOCR](https://github.com/OCR4all/EacyOCR) for accurate OCR capabilities.
- [PIL (Python Imaging Library)](https://pillow.readthedocs.io/) for image processing functionality.
- [ImageIO](https://imageio.github.io/) for reading and writing various image formats.
- [SQLAlchemy](https://www.sqlalchemy.org/) for database connection and management.
- [PyMySQL](https://pymysql.readthedocs.io/) for interacting with SQL Server using Python.

