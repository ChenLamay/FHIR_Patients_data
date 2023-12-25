# FHIR Patient Encounter Data Modeling and SQL Queries

## Overview
This project involves modeling patient encounter data received in Fast Healthcare Interoperability Resources (FHIR) format into a relational database and writing SQL queries to analyze the data.

### Data Modeling
#### Tables Created:
1. **Appointments**
2. **Patients**
3. **Diagnosis**
4. **System Inputs**
5. **Locations**
6. **Hospitals**
7. **Doctors**

### Data Formatting: 
Reshaped an unreadable JSONL file by converting it into a readable JSON format, facilitating subsequent data handling.

### Data Organization:
Structured the data using Regex, streamlining information extraction and creating an efficient data structure.

### Database Setup:
Established relational tables, uploaded entities, and connected data points for a cohesive database schema.

### SQL Query Execution:
Executed SQL queries to retrieve requested values, obtaining pertinent insights from the structured data.

### Result Analysis:
Generated insightful results, allowing easy access to valuable healthcare encounter data for analysts' queries.


### How to Run
1. **Data Preparation**:
   - Place the FHIR JSONL file in the `data/` directory.
   - Open the Jupyter notebook (`notebooks/FHIR_Data_Processing.ipynb`).
   - Run the notebook end-to-end to model the data and execute SQL queries.

### Notes
- The data processing steps are thoroughly documented within the notebook.
- Ensure the SQL database connection is properly configured before running the notebook and insert your postgress password in the code.

