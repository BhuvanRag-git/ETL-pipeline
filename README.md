📊 ETL Pipeline Project

This project demonstrates an ETL (Extract, Transform, Load) pipeline built in Python.
It extracts data from multiple file formats (CSV, JSON, XML), transforms it into a consistent format (metric units), and loads the results into a structured CSV file.
All steps are logged for traceability.

🎯 Objectives

Extract data from CSV, JSON, and XML files.

Transform measurements:

Convert height from inches → meters.

Convert weight from pounds → kilograms.

Load the cleaned data into a CSV file.

Log every ETL step with timestamps for auditing.

⚙️ Installation

Clone this repo and install dependencies:

git clone https://github.com/<your-username>/ETL-pipeline.git
cd ETL-pipeline
pip install -r requirements.txt

🚀 Usage

Run the ETL pipeline:

python etl_pipeline.py

📂 Outputs

✅ transformed_data.csv → Final structured dataset (metric units).

✅ log_file.txt → Logs of ETL operations (Extraction, Transformation, Loading).

📁 Project Structure
ETL-pipeline/
│── etl_pipeline.py        # Main ETL script
│── requirements.txt       # Dependencies
│── README.md              # Project documentation
│── log_file.txt           # ETL logs
│── transformed_data.csv   # Final output

🛠️ Tech Stack

Python 3

pandas → Data manipulation

glob → File handling

xml.etree.ElementTree → XML parsing

datetime → Logging with timestamps

🔐 Secure Code Practices

No credentials are hardcoded.

Follows PEP-8 coding standards.

Modular design with separate functions for Extract, Transform, Load, and Logging.

👨‍💻 Author

Bhuvanikha Rag
