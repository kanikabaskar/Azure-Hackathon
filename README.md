# Document Intelligence with Azure OpenAI

## Project Overview
This project was developed for a hackathon, focusing on enhancing healthcare data management. The solution aims to automate the extraction and analysis of information from medical forms and prescriptions using Azure AI and OpenAI technologies. By converting paper forms into structured digital formats and visualizing data insights, healthcare providers can streamline patient record management, improve decision-making, and offer better patient care.

## Problem Statement
Traditional data entry in healthcare is time-consuming, error-prone, and often results in fragmented data stored across multiple formats. This project addresses key issues such as:
- **Manual Data Entry**: Inefficient and error-prone, leading to delays.
- **Data Fragmentation**: Inconsistent records that hinder a unified patient view.
- **Limited Access to Real-Time Insights**: Delays in accessing updated patient data, crucial for emergency decision-making.

## Solution Approach
Our solution automates medical data processing using Azure's OCR and AI capabilities for accurate extraction and structuring of data. Key features include:
- **Data Extraction**: Using Azure Form Recognizer to capture and digitize information from forms.
- **Summarization and Querying**: Implementing OpenAI's API for natural language processing, enabling healthcare providers to ask questions and receive instant summaries.
- **Data Storage and Management**: Secure storage on Azure Blob Storage for accessible and organized record-keeping.
- **Data Visualization**: A Power BI dashboard presents insights on patient demographics, treatment patterns, and hospital usage.

## Technologies Used
- **Azure Form Recognizer**: For document intelligence and data extraction.
- **Azure OpenAI**: For natural language summarization and querying.
- **Azure Data Factory**: To manage large volumes of data efficiently.
- **Azure Blob Storage**: Secure storage for patient records.
- **Power BI**: Visualization of data insights for easy interpretation.

## Project Workflow
1. **Data Extraction with Azure Form Recognizer**: Medical forms and prescriptions are digitized, extracting patient information and treatment details.
2. **Summarization & Querying Using OpenAI**: Healthcare providers can use natural language queries to retrieve specific information about a patient's medical history or treatment.
3. **Data Storage and Accessibility**: Extracted data is securely stored in Azure Blob Storage, ensuring easy access and compliance with healthcare regulations.
4. **Data Visualization with Power BI**: A comprehensive dashboard provides visual insights into patient demographics, trends, and usage patterns, aiding in data-driven decision-making.

### [Power BI Dashboard Link](your-dashboard-link-here)
This link provides access to the Power BI dashboard for viewing visual insights on patient trends and healthcare usage.

## Installation and Setup
1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/Document-Intelligence-Azure.git
    cd Document-Intelligence-Azure
    ```
2. **Azure Setup**
   - Set up an Azure account and configure the following services:
     - **Azure Form Recognizer**
     - **Azure OpenAI Services**
     - **Azure Data Factory**
     - **Azure Blob Storage**
     - **Power BI Integration**

3. **Environment Variables**
   - Configure your environment with the necessary Azure API keys and endpoints.

## Usage
1. **Run the Document Extraction**
   - Upload documents to Azure Blob Storage for processing.
   - The Form Recognizer will extract data and save it to structured formats.
   
2. **Query Patient Data Using OpenAI**
   - Use natural language queries to retrieve specific patient information.
   
3. **View Insights on Power BI Dashboard**
   - Visualize extracted data and trends on the Power BI dashboard.

## Future Enhancements
- **Enhanced NLP for Summarization**: Improve query handling with additional OpenAI models.
- **Scalability for Larger Healthcare Networks**: Expand the system to handle larger, multi-hospital data volumes.
- **Integration with Additional Healthcare APIs**: Incorporate other healthcare data systems for a more comprehensive patient record system.

## Contributors
- Bhuvaneshwar V
- Devesh S B
- Harshavardhini M
- Kanika B
- Srijith R

---

This project demonstrates the potential of Azure Document Intelligence and OpenAI in addressing data automation challenges in healthcare, streamlining patient record management, and supporting data-driven healthcare decisions.
