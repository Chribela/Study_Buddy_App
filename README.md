# StudyBuddy App

The StudyBuddy app is a web application built using Django that aims to facilitate online learning and collaboration among students. It provides features for users to create study rooms, engage in discussions, and exchange messages on various topics. Students can join existing rooms or create their own study spaces to connect with peers and enhance their learning experience.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- - [Login and Registration](#login-and-registration)
- - [Home Page](#home-page)
- - [Room Creation](#room-creation)
- - [Room Interaction](#room-interaction)
- - [User Profile](#user-profile)
- - [Topics](#topics)
- - [Activity](#activity)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The StudyBuddy app is designed to foster collaboration and communication among students in an online learning environment. It enables users to create study rooms centered around specific topics, engage in meaningful discussions, and exchange messages with fellow students. The app enhances students' learning experiences by providing a platform for knowledge sharing and interaction.

## Features

### Login and Registration

- Users can register for an account or log in to their existing account.
- User authentication and session management ensure secure access to the app.

### Home Page

- The home page displays a list of study rooms and their corresponding topics.
- Users can search for rooms and topics using a search query.

### Room Creation

- Authenticated users can create study rooms by providing a room name, topic, and description.
- Topics are created dynamically based on user input.

### Room Interaction

- Users can join study rooms, view room details, and participate in discussions.
- Participants can post messages and engage in conversations within the room.
- Room hosts have the ability to manage room content, including updating and deleting rooms.

### User Profile

- Users can view their profiles, including their created rooms and engagement in discussions.
- Profile pages provide insights into a user's activity within the app.

### Topics

- Users can explore and search for topics relevant to their interests.
- Topics are linked to specific study rooms, allowing users to discover and join rooms related to their chosen topics.

### Activity

- The activity page displays a feed of messages exchanged within study rooms.
- Users can review the discussions and interactions happening across the app.

## Project Structure

The project structure is organized as follows:

- `studybuddy/`: The main Django app directory.
  - `models.py`: Defines the database models for rooms, topics, messages, and users.
  - `forms.py`: Contains forms for user registration, room creation, and user profile updates.
  - `views.py`: Implements the various views and functionalities of the app.
  - `templates/`: Contains HTML templates for rendering the app's pages.

## Technologies Used

- Django
- Python
- HTML
- CSS
- JavaScript

## Installation

1. Clone the repository: `git clone https://github.com/your-username/studybuddy.git`
2. Navigate to the project directory: `cd studybuddy`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Set up the database: `python manage.py migrate`
5. Create a superuser: `python manage.py createsuperuser`

## Usage

1. Run the development server: `python manage.py runserver`
2. Open your web browser and visit: `http://localhost:8000`
3. Register an account or log in with your credentials.
4. Explore study rooms, join discussions, and create your own study spaces.

## Contributing

Contributions are welcomed! To contribute to the StudyBuddy app:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature/your-feature-name`
3. Implement your changes and commit: `git commit -m "Add your feature"`
4. Push your changes to your branch: `git push origin feature/your-feature-name`
5. Open a pull request on the main repository.

## License

This project is licensed under the MIT License.

---

 

Connect with on LinkedIn:
- ## www.linkedin.com/in/danny-ercy-ndikuriyo
"# Study_Buddy_App" 
