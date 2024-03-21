# BlogsMania

![Flask Blog System Logo](./public/images/logo.png)

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Description

The **BlogsMania** is a web application built using Flask and SQLite, designed to facilitate blog management and interaction. It provides users with the ability to register, login, and access blogs. Users can read blogs, like them, and leave comments. However, only administrators have the privilege to create and publish new blog posts. With its intuitive interface and comprehensive features, this system aims to enhance the blogging experience for both writers and readers.

### Homepage
![Screenshot](./public/images/homepage.png)

### Blog Post
![Screenshot](./public/images/blog-post.png)

### User Dashboard
![Screenshot](./public/images/user-dashboard.png)

## Features

- User authentication system for registration and login.
- Role-based access control with administrators and regular users.
- Blog viewing, liking, and commenting functionalities for users.
- Administrator-exclusive privilege to create and publish new blog posts.
- Responsive and user-friendly design for seamless interaction.

## Technologies Used

The Flask Blog System is built using the following technologies:

- **Python** - As the primary programming language.
- **Flask** - For creating the web application and handling routes.
- **SQLite** - As the database for storing user data and blog posts.



## Usage

- Open your web browser and access the Flask Blog System website.
- Register for a new account or login if you already have one.
- Explore the available blogs, read them, and interact by liking or commenting.
- Administrators can access the dashboard to create and publish new blog posts.

## Folder Structure
The project structure is organized as follows:

- static/ - Contains static assets like CSS, client-side JavaScript, and images.
- templates/ - Includes HTML templates for rendering pages.
- routes/ - Defines Flask routes and handles HTTP requests.
- models/ - Contains SQLAlchemy models for data storage.
- forms/ - Defines Flask-WTF forms for user input validation.
Contributing

We welcome contributions from the community to improve the **BlogsMania**. If you'd like to contribute, please follow these guidelines:

## Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and commit them with clear, concise commit messages.
- Push your changes to your forked repository.
- Create a pull request to the main repository with a detailed description of your changes.

## Acknowledgments
- Special thanks to the open-source community for their valuable contributions and inspiration.
