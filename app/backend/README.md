# Backend Application Documentation

## Overview
This document provides an overview of the backend application for the Azure Search OpenAI Demo.

## Prerequisites
- Python 3.8 or higher
- Azure account
- Azure Cognitive Search service
- OpenAI API key

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-repo/azure-search-openai-demo.git
    cd azure-search-openai-demo/app/backend
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Configuration

1. Create a `.env` file in the `backend` directory and add the following environment variables:
    ```env
    AZURE_SEARCH_SERVICE_NAME=your-search-service-name
    AZURE_SEARCH_INDEX_NAME=your-index-name
    AZURE_SEARCH_API_KEY=your-search-api-key
    OPENAI_API_KEY=your-openai-api-key
    ```

## Running the Application

1. Start the backend server:
    ```sh
    python app.py
    ```

2. The application will be available at `http://localhost:5000`.

## API Endpoints

- `GET /search`: Search the Azure Cognitive Search index.
- `POST /generate`: Generate text using OpenAI API.

## License
This project is licensed under the MIT License. See the [LICENSE](../LICENSE) file for details.

## Contributing
Contributions are welcome! Please see the [CONTRIBUTING](../CONTRIBUTING.md) file for guidelines.

## Contact
For any questions or issues, please open an issue on the [GitHub repository](https://github.com/your-repo/azure-search-openai-demo).
