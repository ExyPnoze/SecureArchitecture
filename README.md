# DummyBanking - Fictitious Banking Transaction Application

DummyBanking is a web application currently under development using Django, designed to simulate a fictional banking site allowing users to conduct transactions among themselves.

## Features

- **User Authentication:** Users can sign up, log in, and manage their accounts.
- **Transactions:** Perform transactions between users with specified amounts.

## Prerequisites

- Python 3.x
- Django
- Other dependencies specified in `requirements.txt`

## Installation

1. Clone this repository: `git clone https://github.com/ExyPnoze/SecureArchitecture`
2. Navigate to the project directory: `cd SecureArchitecture`
3. Create a virtual environment: `python -m venv venv`
4. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS and Linux: `source venv/bin/activate`
5. Install dependencies: `pip install -r requirements.txt`
6. Apply migrations: `python manage.py migrate`
7. Start the server: `python manage.py runserver`

## Usage

1. Access the application via your web browser at: `http://localhost:8000`
2. Sign up as a user or log in with credential in users.md.
3. Explore the features to conduct transactions between users.

## Security Notice

**Important:** This project is created for educational purposes to simulate a banking environment. It does not handle real money or sensitive financial information. Ensure that this application is used in a controlled environment and is not intended for actual financial transactions. The `users.md` file is used for demonstration purposes and does not reflect secure credential storage practices. Always follow best security practices and avoid using real or sensitive personal information in this environment.

## Contributions

Contributions are welcome! If you'd like to contribute to this project, follow these steps:

1. Fork the repository
2. Create a branch for your modifications: `git checkout -b feature/feature-name`
3. Make your changes and commit: `git commit -m "Add feature X"`
4. Push your changes to your fork: `git push origin feature/feature-name`
5. Open a Pull Request to discuss the proposed changes.

## Author

- Guiset Léandre [@ExyPnoze](https://github.com/ExyPnoze)
