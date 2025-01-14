# Weather Dashboard

A Python-based weather dashboard application that fetches and displays real-time weather data and forecasts for any location, using AWS for cloud resource management.

## Project Structure
weather-dashboard/
  src/
    __init__.py
    weather_dashboard.py
  tests/
  data/
  .env
  .gitignore
  requirements.txt

## About
The Weather Dashboard is a Python-based application that uses AWS services to fetch and display real-time weather data. It leverages APIs for weather data and stores user preferences securely.

## Prerequisites
- Python 3.12 installed on your system.
- AWS CLI installed and configured.
- An AWS S3 bucket created for storing logs.
- An OpenWeather API key for fetching weather data.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/cmmolina123/30days-weather-dashboard.git

2. Set up a virtual environment:
python3 -m venv venv
source venv/bin/activate

3. Install dependencies:
pip install -r requirements.txt

4. Configure environment variables (.env): Create a .env file and add the following:
OPENWEATHER_API_KEY=your_api_key
AWS_BUCKET_NAME=your_bucket_name

5. Configure AWS credentials:
aws configure

6. Run the application:
python src/weather_dashboard.py

## Features
- Fetch real-time weather data for any location.
- 5-day weather forecast.
- Integration with AWS S3 for storing application logs.
- Secure configuration using environment variables.
- User-friendly CLI interface.

## Technologies Used
- Python 3.12
- AWS S3 for storage
- AWS CLI for deployment and configuration
- `boto3` for AWS SDK integration
- `requests` for fetching weather data
- `python-dotenv` for environment variable management

## What I Learned
- AWS S3 bucket creation and management
- Environment variable management for secure API keys
- Python best practices for API integration
- Git workflow for project development
- Error handling in distributed systems
- Cloud resource management