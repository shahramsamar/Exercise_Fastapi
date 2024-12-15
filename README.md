# FastAPI Exercise CRUD Search

A Python project that demonstrates how to build a CRUD (Create, Read, Update, Delete) application using **FastAPI** with integrated search functionality. This project helps you understand how to create and manage resources in a FastAPI application while allowing for search capabilities.

## Features

- **CRUD Operations**: Implements basic CRUD operations (Create, Read, Update, Delete) for resource management.
- **Search Functionality**: Allows users to search for resources using specific query parameters.
- **FastAPI Integration**: Leverages FastAPI's powerful features to build a fast and efficient web application.
- **Pydantic Models**: Uses Pydantic for data validation and automatic documentation generation.

## Requirements

- **Python 3.x**
- **FastAPI**
- **SQLAlchemy** (for database integration)
- **Uvicorn** (for running the FastAPI application)

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/shahramsamar/Fastapi-Exercise-Crud-Search.git
    cd Fastapi-Exercise-Crud-Search
    ```

2. **Install Dependencies:**

    If you're using `pip`, run:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Application**:

    To run the FastAPI app:

    ```bash
    uvicorn main:app --reload
    ```

### How to Use

- **Add Data**: You can create new resources by sending a POST request to the corresponding endpoint.
- **Search Data**: You can search for resources by sending a GET request with search parameters.
- **Update Data**: Update resources using PUT or PATCH requests.
- **Delete Data**: Delete resources by sending a DELETE request.

### Project Structure

- `main.py`: Contains the FastAPI application, routes, and logic for handling CRUD operations and search functionality.
- `models.py`: Defines the database models using SQLAlchemy.
- `requirements.txt`: Lists necessary libraries like `FastAPI`, `SQLAlchemy`, and `Uvicorn`.

## Contributing

Feel free to fork the project and submit pull requests for new features, improvements, or bug fixes.

## License

This project is open-source and available for educational purposes.
![Alt](https://repobeats.axiom.co/api/embed/eabe6508a91fa38b4ace0060919094363916f544.svg "Repobeats analytics image")
