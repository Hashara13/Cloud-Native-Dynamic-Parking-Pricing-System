# Cloud-Native Dynamic Parking Pricing System

A complete cloud-native parking pricing ecosystem that combines machine learning demand forecasting, dynamic pricing generation, serverless cloud deployment, and a modern web dashboard for real-time parking price visualization.

This project demonstrates an end-to-end implementation of a demand-driven parking pricing system using Azure cloud services and modern web technologies.

---

## Live Demo

Frontend Dashboard:

https://shared-parking-prices.netlify.app/

---

## Project Overview

Traditional parking systems often use fixed pricing regardless of demand fluctuations.

This project introduces a dynamic pricing approach that:

- Forecasts short-term parking demand
- Generates demand-aware parking prices
- Compares dynamic pricing against static pricing
- Deploys pricing logic through Azure Functions
- Provides a responsive web interface for end users

---

## System Architecture

```text
Historical Parking Data
        │
        ▼
Machine Learning Forecasting Models
(Prophet / XGBoost / Random Forest /LSTM / CNN-LSTM / LSTM-GRU / Transformer)
        │
        ▼
Forecast Output CSV
        │
        ▼
Azure Blob Storage
        │
        ▼
Azure Function Pricing Engine API
        │
        ▼
React Web Dashboard
        │
        ▼
End Users
```

---

## Technology Stack

### Machine Learning & Research

- Python
- Pandas
- NumPy
- Prophet
- XGBoost Regressor
- Random Forest Regressor
- LSTM
- CNN-LSTM
- LSTM-GRU
- Transformer
- Jupyter Notebooks

### Cloud Platform

- Microsoft Azure
- Azure Functions
- Azure Blob Storage

### Frontend

- React
- Vite
- JavaScript
- CSS
- Fetch API

### Deployment

- Azure Functions
- Azure Blob Storage
- Netlify

---

# Repository Structure

This solution is divided into three repositories.

---

## 1. Research & Forecasting Repository

Repository:

https://github.com/Hashara13/Dynamic-Parking-Pricing-Engine

### Purpose

Contains the research and development layer of the project.

### Features

- Data preparation pipeline
- Hourly parking demand forecasting
- Dynamic pricing generation
- Static vs dynamic pricing comparison
- Evaluation and validation
- Research experiments and analysis

### Models

- Prophet
- XGBoost Regressor
- Random Forest Regressor
- LSTM
- CNN-LSTM
- LSTM-GRU
- Transformer

### Key Outputs

- Demand forecasts
- Dynamic pricing datasets
- Revenue comparison reports
- Evaluation metrics

---

## 2. Azure Function Pricing API

Repository:

https://github.com/Hashara13/Dynamic-Pricing-Engine-Azure-Function-App

### Purpose

Provides a serverless pricing engine deployed on Microsoft Azure.

### Features

- Reads forecast data from Azure Blob Storage
- Calculates dynamic parking prices
- REST API endpoint
- Serverless architecture
- Scalable and cost-efficient deployment

### Supported Models

- Prophet
- XGBoost Regressor
- Random Forest Regressor

### Cloud Services

- Azure Functions
- Azure Blob Storage

---

## 3. React Web Dashboard

Repository:

https://github.com/Hashara13/shared-parking-Prices

Live Demo:

https://shared-parking-prices.netlify.app/

### Purpose

Provides a modern web interface for viewing dynamic parking prices.

### Features

- Dark professional UI
- Mobile responsive layout
- Search by parking ID
- Dynamic price visualization
- Pagination
- Sticky table headers
- Refresh functionality
- Error handling
- API integration

### Technologies

- React
- Vite
- CSS
- Fetch API

---

# Key Objectives

- Improve parking revenue
- Adapt pricing to demand fluctuations
- Demonstrate cloud-native architecture
- Compare static and dynamic pricing strategies
- Provide scalable deployment architecture
- Deliver an interactive user experience

---

# Project Components

| Layer | Technology |
|---------|------------|
| Forecasting | Prophet, XGBoost, Random Forest, LSTM,CNN-LSTM,LSTM-GRU,Transforme |
| Data Processing | Python, Pandas |
| Storage | Azure Blob Storage |
| Pricing Engine | Azure Functions |
| API Layer | REST API |
| Frontend | React + Vite |
| Hosting | Netlify |
| Cloud Platform | Microsoft Azure |

---

# Future Improvements

- Real-time forecasting
- Azure Static Web Apps deployment
- Automated model retraining
- User authentication
- Interactive analytics dashboard
- Revenue performance reporting
- Multi-location parking support

---

# Author

Hashara Nethmin

Cloud Computing | Full-Stack Development | Machine Learning | Microsoft Azure

---

## Related Repositories

### Research & Forecasting

https://github.com/Hashara13/Dynamic-Parking-Pricing-Engine

### Azure Function Pricing API

https://github.com/Hashara13/Dynamic-Pricing-Engine-Azure-Function-App

### React Web Dashboard

https://github.com/Hashara13/shared-parking-Prices

### Live Application

https://shared-parking-prices.netlify.app/