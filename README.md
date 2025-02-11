# Anime/Manga Management Application

Teammate: Cojocaru Georgiana https://github.com/LisaLisa7

This is a Python application built with PyQt5 that allows you to manage anime and manga entries. It uses an SQLite database to store and retrieve data related to anime/manga titles, including their details. The application features a user-friendly graphical interface built with PyQt5.

## Prerequisites

Before running the application, make sure you have the following installed:

- **Python 3.x**: The programming language used for this application.
- **PyQt5**: A set of Python bindings for Qt libraries to create graphical user interfaces.
- **SQLite3**: An embedded relational database used for storing data locally.

You can install the required Python dependencies using the following command:
```bash
pip install pyqt5 sqlite3
```

## Database

This application uses SQLite as the database to store anime/manga entries. The database is automatically created when the application is run for the first time. It includes a table for storing the entries, and you can perform CRUD operations (Create, Read, Update, Delete) through the app's interface.

The database connection is handled using the SQLite3 library, and the connection is established via the following code:
```bash
import sqlite3 as sl
```

## Features

- **Add Entries**: You can add new anime/manga entries, including details such as title, genre, and status.
- **View Entries**: View a list of all anime/manga entries in the database.
- **Update Entries**: Update the information of an existing anime/manga entry.
- **Delete Entries**: Remove anime/manga entries from the database.

## Dependencies

This project requires the following dependencies:

- **PyQt5**: For building the graphical user interface.
- **sqlite3**: For interacting with the SQLite database.
