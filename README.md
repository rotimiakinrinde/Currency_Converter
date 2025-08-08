# Currency Converter – Real-Time FX with Python & ExchangeRatesAPI

## Project Overview

This project is a **real-time currency exchange tool** built using Python. It integrates with [ExchangeRatesAPI.io](https://exchangeratesapi.io/) to retrieve live FX rates and processes the response using `pandas` for fast analysis and display.

It serves as a practical example of:
- Consuming external RESTful APIs
- Handling secrets securely using `.env` files
- Processing and analyzing JSON data
- Building a clean and reproducible data pipeline in Python
- 

## ⚙️ Architecture & Workflow

    A  [.env file with API key] --> B[Python loads environment variables]
 
    B --> C[Request to ExchangeRatesAPI]
    
    C --> D[API returns JSON response]
    
    D --> E[pandas parses and flattens data]
    
    E --> F[DataFrame displayed in notebook]


## Rationale

- To practice working with **APIs** and real-world financial data  
- To demonstrate clean data processing using **pandas**  
- To apply secure environment management using `.env` files  
- To show how even a simple tool can automate everyday tasks  

This project is also part of my broader goal: building small, useful tools that bring real-world value through automation and data.

## How It Works

1. Loads your API key securely using `python-dotenv`
2. Sends a request to the ExchangeRatesAPI for the latest currency rates
3. Parses and displays the rates in a readable format using `pandas`

## Tech Stack

- **Python 3.7+**
- `requests` – for calling the exchange rate API  
- `pandas` – for processing and displaying data  
- `python-dotenv` – for secure API key management  
- `Jupyter Notebook` – for step-by-step interaction


