# Python CI/CD Project with Pytest

This project demonstrates a simple Python application with automated testing using Pytest and CI/CD pipeline using GitHub Actions.

## Project Structure

my-project/
│
├── app.py
├── calculator.py
├── test_app.py
├── test_unit.py
├── test_integration.py
├── requirements.txt
├── Dockerfile
└── .github/workflows/ci.yml

## Features

- Simple Python calculator functions
- Automated testing using Pytest
- CI/CD pipeline using GitHub Actions
- Docker support

## Installation

Clone the repository:

git clone https://github.com/aishu0203/my-project.git

Navigate to the project folder:

cd my-project

Install dependencies:

pip install -r requirements.txt

## Run the Application

python app.py

## Run Tests

pytest

Example output:

4 passed in 0.05s

## CI/CD Pipeline

This project uses GitHub Actions to automatically:

- Install Python
- Install dependencies
- Run Pytest tests

Every time code is pushed to GitHub, the pipeline runs automatically.

## Author

Aishu