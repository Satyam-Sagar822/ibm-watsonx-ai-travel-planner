# AI Travel Planner using IBM watsonx.ai

An AI-powered travel planner built using Langflow and IBM watsonx.ai 
Granite model that provides personalized travel plans with live 
weather updates.

## Features
- Live weather data integration
- Budget calculation and breakdown
- Day-wise itinerary generation
- Hotel and transport recommendations
- Packing list based on weather
- Local attractions and food recommendations

## Tech Stack
- Langflow
- IBM watsonx.ai (Granite model)
- OpenWeatherMap API

## Prerequisites
- Langflow installed
- IBM Cloud account
- IBM watsonx.ai service (Lite plan or above)
- OpenWeatherMap API key (free)

## Setup Instructions

### 1. Install Langflow
pip install langflow

### 2. Run Langflow
langflow run

### 3. Import Flow
- Open Langflow in browser
- Click Import
- Select the AI-Travel-Planner-solved.json file

### 4. Configure API Keys
In the flow, update these credentials:
- IBM watsonx.ai API Key (from cloud.ibm.com/iam/apikeys)
- IBM watsonx.ai Project ID (from us-south.dataplatform.cloud.ibm.com)
- IBM watsonx.ai Endpoint: https://us-south.ml.cloud.ibm.com
- OpenWeatherMap API Key (from openweathermap.org)

### 5. Run the Flow
- Click Playground
- Enter your travel query like:
  "I am from Delhi. I want to travel to Goa. 
   5 days trip. Budget 30000."

## Demo
<img width="1542" height="780" alt="Screenshot 2026-06-07 124703" src="https://github.com/user-attachments/assets/ff06de40-16e2-4508-83cf-fd90bf7f360e" />


## Author
Satyam Sagar
