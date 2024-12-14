Article Management System

A simple system to manage authors, magazines, and articles using a relational database (SQLite). The system allows creating, querying, and managing articles and their relationships with authors and magazines.

#Features

Manage authors and magazines.
Add and manage articles with titles, content, and associated authors and magazines.
Query articles, authors, and magazines with their relationships.

#Technologies Used

Python: Main programming language.
SQLite3: Database for storing data.
SQLAlchemy (optional): Can be added for ORM-based operations.

#Installation

Prerequisites:
Python 3.x
Steps:
Clone the repository:
bash
Copy code
git clone https://github.com/Joy-mwende63/Moringa-FT09-phase-3-code-challenge
cd Moringa-FT09-phase-3-code-challenge
Install dependencies (preferably in a virtual environment):
bash
Copy code
pip install -r requirements.txt

#Usage

Run the Application:

bash
Copy code
python3 app.py
Interact with the system:

Input author’s name, magazine details, and article content when prompted.
View Results:

The application displays the inserted records for authors, magazines, and articles, showing their relationships.

#Database Schema

authors: Stores author information.
magazines: Stores magazine details.
articles: Stores articles, linked to authors and magazines.

#Code Structure

app.py: Main script to run the application.
database/connection.py: Manages database connections.
database/setup.py: Creates the necessary tables.
models/: Contains models for Article, Author, and Magazine.
Contributing
Feel free to fork, submit issues, or create pull requests. Contributions are welcome!

#License

MIT License (c) 2024

