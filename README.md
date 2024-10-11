# Invoice Extractor Using Google Gemini Pro LLM

## Overview

This project implements an Invoice Extractor that utilizes the Google Gemini Pro LLM (Large Language Model) to extract key information from invoices, such as the invoice number, date, total amount, and line items. The application is designed to help automate the processing of invoices and improve data entry accuracy.

## Features

Upload invoices in various formats (PDF, JPG, PNG)

Automatic extraction of key invoice details

User-friendly web interface

Option to download extracted data in structured formats (CSV, JSON)

Secure handling of uploaded documents

## Technologies Used

Backend: Streamlit or Flask (or FastAPI)

Frontend: HTML

LLM: Google Gemini Pro

Deployment: Docker (optional)

## Requirements

Python 3.x

Streamlit or Flask or FastAPI

requests (for API calls to Google Gemini)

pdf2image (for PDF processing)

Other dependencies (listed in requirements.txt)

## Usage

Navigate to the home page of the application.

Upload your invoice file (PDF, JPG, or PNG).

Click the "Extract" button to process the invoice.

The extracted information will be displayed, and you can download it in your preferred format (CSV or JSON).

## Deployment

To deploy the app, consider using platforms like Heroku, AWS, or Google Cloud. Ensure you have the necessary environment variables and configurations set up
