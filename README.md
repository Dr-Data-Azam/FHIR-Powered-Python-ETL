# FHIR Powered Python ETL Project for Healthcare Interoperability

## Visit the project website
<a href="https://dr-data-azam.github.io/FHIR-Powered-Python-ETL/index.html">FHIR-Powered-Python-ETL-Project-Website</a>

## Overview
The **FHIR Powered Python ETL** project demonstrates the use of the **FHIR (Fast Healthcare Interoperability Resources)** standard for extracting, transforming, and loading (ETL) healthcare data. This project focuses on integrating healthcare data from **OpenEMR FHIR** and **SNOMED CT** to a **Primary Care FHIR server**. The system extracts patient and condition data, processes it using SNOMED codes, and then uploads the transformed data to the Primary Care FHIR server, following industry-standard interoperability practices.

This project leverages the **FHIR API**, **OAuth2 authentication**, and **SNOMED CT codes** to ensure secure and standardized data exchange, making it a step towards improving healthcare data interoperability.

### Key Learning Outcomes:
- **FHIR**: I learned how to integrate healthcare data using the **FHIR standard** and how to structure and post **FHIR resources** (e.g., Patient, Condition) using the API.
- **APIs**: I gained practical experience in working with **RESTful APIs**, including authentication, making GET and POST requests, and handling responses from healthcare systems.
- **OAuth2**: The project involved securing the FHIR API with **OAuth2** access tokens for safe and authorized communication between the system and the API.
- **Data Interoperability**: I developed an understanding of how to ensure **data interoperability** across different healthcare systems, focusing on the integration of patient data, conditions, and other clinical information.

## Project Structure

FHIR-Powered-Python-ETL/
- **│**
- **├──** FHIR_ETL_Project/ # Main ETL project code
├── images/ # Folder for images and diagrams
├── index.html # Homepage for the website
├── about.html # About the project page
├── bpm_model.html # BPMN model page
├── etl_pipeline.html # ETL pipeline visualization
├── insights.html # Insights page
├── styles.css # Custom styles for the website
├── README.md # Project documentation
│
└── .gitignore # List of files/folders to ignore by Git

## GitHub Pages Website
This project also includes a static website hosted via GitHub Pages. The website provides visualizations of the ETL pipeline, project insights, and team contributions. You can access the live website here:

## Technologies Used
Python 3.x: Used for scripting the ETL process and handling data extraction, transformation, and loading.
FHIR (Fast Healthcare Interoperability Resources): A modern healthcare data exchange standard used for extracting and posting patient data.
SNOMED CT: Used for standardized medical coding to classify clinical information.
OAuth2: Used for secure authentication when accessing the FHIR API.
Requests: Python library for making HTTP requests to fetch and send data to FHIR servers.
JSON: Used to structure data for interaction with APIs and for data storage.
GitHub Pages: Used to host a static website displaying project details and visualizations.

## Learning Experience
Throughout this project, I gained significant knowledge about healthcare data interoperability. By using FHIR, I was able to understand how standardized data exchange works in healthcare settings. The use of OAuth2 for authentication taught me how to securely manage access tokens when interacting with healthcare APIs.
I also learned how to work with RESTful APIs, handle requests and responses, and ensure that the data being posted to the server adheres to FHIR standards. The integration of SNOMED CT provided valuable insight into how clinical codes are used to standardize healthcare data, making it easier to manage and exchange.
