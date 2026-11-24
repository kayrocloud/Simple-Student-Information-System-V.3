# Simple-Student-Information-System-V.3
A web-based Student Information System developed using Flask, Python, HTML, CSS, JavaScript, and MySQL. The system provides basic student record management and allows users to manage information related to students, courses, and colleges through CRUD operations.

## Features
- **Student Management** – Add, view, update, and delete student records.
- **Course Management** – Manage available courses and their information.
- **College Management** – Manage college records and details.
- **Database Integration** – Uses MySQL for storing and managing application data.
- **Web Interface** – Provides a simple and user-friendly interface for record management.

## Technologies Used
| Technology | Purpose |
|---|---|
| Python | Backend development and application logic |
| Flask | Web application framework and server-side routing |
| HTML | Page structure and visual styling |
| JavaScript | Frontend interactivity and dynamic functionality |
| MySQL | Relational database management and CRUD operations |

## Folders
- **Models** - Manage records and database interactions.
- **Routes** - Defines application routes for managing records, requests, and CRUD operations.
- **Static** - JS files provides interactive frontend functionality. Folder also include images.
- **Templates** - Contains HTML templates for the application's navigation and CRUD interfaces across students, courses, and colleges.

## Files
- **config.py** - Manages application configuration, including Flask settings, MySQL database credentials, and Cloudinary integration using environment variables.
- **main.py** - Initializes the Flask application, registers routes and configurations, and runs the web server.
