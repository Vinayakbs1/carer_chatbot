# Career Chatbot

An AI-powered career guidance chatbot built with Azure services that helps users explore career paths based on their skills and interests.

## Features

- Skill analysis and career path recommendations
- Interactive chat interface
- Career details and information
- Skill development recommendations
- Chat history tracking

## Technologies Used

- Azure Language Service for natural language understanding
- Azure Cosmos DB for data storage
- Azure Functions for serverless computing
- Azure Static Web Apps for hosting
- Flask for the web application
- Python for backend logic

## Setup Instructions

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Set up environment variables in `.env` file
4. Run the application: `python app.py`

## Environment Variables

Required environment variables:

- COSMOS_URI
- COSMOS_KEY
- COSMOS_DATABASE
- COSMOS_CONTAINER
- LANGUAGE_ENDPOINT
- LANGUAGE_KEY
- AZURE_STORAGE_CONNECTION_STRING
- AZURE_STORAGE_CONTAINER
- AZURE_FUNCTION_URL
- SECRET_KEY

## Project Structure

- `/templates` - HTML templates
- `/models` - Machine learning models
- `/static` - Static assets
- `app.py` - Main Flask application
- `azure_functions.py` - Azure Functions client
- `cosmos_db.py` - Cosmos DB manager
- `language_service.py` - Azure Language Service client
- `prediction.py` - Career prediction logic

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.