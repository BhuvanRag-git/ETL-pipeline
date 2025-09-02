# ETL-pipeline
# A Comprehensive ETL Workflow with Python for Data Engineers

## 📌 Project Overview
This project demonstrates a complete **Extract, Transform, Load (ETL)** pipeline using **Python**.  
It extracts data from multiple file formats (**CSV, JSON, XML**), transforms the data (unit conversions), and loads it into a structured CSV file.  
The project also includes **logging** to track each step for monitoring and debugging.  

---

## 🎯 Objectives
- Extract data from **CSV, JSON, XML** files.  
- Transform the extracted data (heights → meters, weights → kilograms).  
- Load the transformed data into `transformed_data.csv`.  
- Maintain a log file `log_file.txt` with timestamps for each ETL phase.  
- Ensure the project follows **secure coding, modular design, and PEP 8 standards**.  

---

## 🛠️ Technologies Used
- **Python 3.x**
- **pandas** (data handling)
- **xml.etree.ElementTree** (parsing XML)
- **glob** (file handling)
- **datetime & logging** (progress tracking)

---

## 📂 Dataset
Download the dataset from IBM Skills Network:  
[Dataset Link](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0221EN-SkillsNetwork/labs/module%206/Lab%20-%20Extract%20Transform%20Load/data/source.zip)

Unzip it into your project directory:
```bash
unzip source.zip -d ./unzipped_folder
