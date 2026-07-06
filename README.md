# Online Notes Sharing System

## Overview
The Online Notes Sharing System is a collaborative platform that allows users to create, share, and manage notes. Built with a PHP backend and a MySQL database, this application provides a user-friendly interface for note-taking and sharing.

## Features
- User registration and authentication
- Create, read, update, and delete notes
- Responsive design using Bootstrap
- Dynamic interactions with jQuery
- Secure handling of user data

## Technologies Used
- PHP
- MySQL
- HTML5
- CSS3
- Bootstrap
- jQuery

## Project Structure
```
online-notes-sharing-system
├── app
│   ├── config.php
│   ├── database.php
│   ├── functions.php
│   └── models
│       ├── Note.php
│       └── User.php
├── public
│   ├── index.php
│   ├── login.php
│   ├── register.php
│   ├── dashboard.php
│   ├── note.php
│   ├── assets
│   │   ├── css
│   │   │   └── styles.css
│   │   ├── js
│   │   │   └── scripts.js
│   │   └── vendor
│   │       ├── bootstrap
│   │       └── jquery
├── sql
│   └── schema.sql
├── .gitignore
├── composer.json
└── README.md
```

## Installation
1. Clone the repository to your local machine.
2. Set up a local server environment using XAMPP or similar.
3. Start Apache and MySQL.
4. If needed, set the database environment variables for your server:
   - `DB_HOST`
   - `DB_USER`
   - `DB_PASS`
   - `DB_NAME`
   - `APP_URL`
5. Access the application via your web browser at `http://localhost:8000/login.php` when using the built-in PHP server, or at `http://localhost/online-notes-sharing-system/public/login.php` with XAMPP.

## Quick deployment for the web
- Upload the project files to your hosting account.
- Point the public web root to the `public` folder if your host allows it.
- Set the database variables in your hosting control panel.
- The app will create the required database tables automatically on first use.

## Usage
- **Register**: Create a new account by navigating to the registration page.
- **Login**: Access your account using the login page.
- **Dashboard**: View and manage your notes from the dashboard.
- **Notes**: Create new notes or edit existing ones.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is open-source and available under the MIT License.