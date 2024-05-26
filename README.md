# Backend - User Profile Website

## Overview
The backend of the user profile website is built using PHP and MySQL. It provides the necessary APIs and database management to handle user data and profiles.

## Project Structure
The backend directory contains the following structure:
- **api**: Contains PHP scripts for handling API endpoints.
- **db.sql**: SQL script for database setup and structure.
- **htdocs**: The root directory for the XAMPP server environment.

## Getting Started
To set up and run the backend:
1. Ensure you have XAMPP or a similar server environment installed.
2. Move the `backend` directory to the XAMPP's `htdocs` directory.
3. Start the Apache and MySQL services from the XAMPP control panel.

## Database Setup
To set up the database:
1. Open phpMyAdmin from the XAMPP control panel.
2. Create a new database.
3. Import the database structure from the `db.sql` file located in the `backend` directory.

## API and Endpoints
The backend includes a RESTful API to handle user data. The API endpoints are as follows:
- `/api/users` - GET, POST, PUT, DELETE user data
- `/api/profiles` - GET, POST, PUT, DELETE profile data

## Contributing
Contributions to the backend codebase are welcome! Please fork the repository and submit a pull request with your changes.

