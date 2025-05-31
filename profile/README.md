
![image](https://github.com/user-attachments/assets/65cd0d97-a1d9-456f-9683-bd3a7704839c)


# Al-Huda Academy Graduation Project

This organization contains the frontend and backend codebases for Al-Huda Academy, a platform for advanced Quran recitation, exploration, and interactive learning.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Architecture](#architecture)
- [API Documentation](#api-documentation)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
---

## Overview

Al-Huda Academy is a graduation project focused on Quranic education. The platform consists of two primary components:

- **Frontend**: Provides the user interface for students, teachers, and administrators.
- **Backend**: Supplies secure APIs, search, user management, and administrative controls.

The system is designed to support Quranic learning by offering detailed Surah explanations, categorized Athkar, user and group management, and other features.

---

## Features

- User authentication (registration, login)
- Search across Surahs and verses
- Detailed Surah explanations (tafsir)
- Secure account management
- Admin panel for user and content management
- Categorized Athkar with filtering and pagination
- Family link verification (parent-child accounts)
- Teaching methods management
- Participant management by user ID
- Multi-language support
- Group goals and daily schedules management
- Memorization group organization
- Notification system
- Role and permission management

---

## Technologies Used

### Backend
- Node.js
- Express.js
- MongoDB
- Sequelize (for SQL-based models)
- JWT for authentication

### Frontend
- Flutter
- GetX (for state management)

---

## Installation

### Backend

1. Clone the repository:
   ```sh
   git clone https://github.com/DiaaHSharqawi/Al-Huda-Academy-Backend.git
   cd Al-Huda-Academy-Backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Configure environment variables:
   - Create a `.env` file in the root directory.
   - Add the required configuration (refer to `.env.example` if available).
4. Start the server:
   ```sh
   npm start
   ```

### Frontend

1. Clone the repository:
   ```sh
   git clone <frontend-repo-url>
   cd Al-Huda-Academy-Frontend
   ```
2. Install dependencies:
   ```sh
   flutter pub get
   ```
3. Run the application:
   ```sh
   flutter run
   ```

---

## Architecture

The platform uses the Model-View-Controller (MVC) architecture:

- **Model**: Handles data and database operations.
- **View**: Formats responses for the client (typically JSON).
- **Controller**: Processes requests, interacts with models, and returns responses.

---

## API Documentation

API details are available in the backend repository or via the `/docs` endpoint if enabled.

- [API Documentation](https://github.com/DiaaHSharqawi/Al-Huda-Academy-Backend#api-documentation)

---

## Project Structure

```
Al-Huda-Academy-Graduation-Project/
├── Al-Huda-Academy-Backend/   # Node.js/Express API server
├── Al-Huda-Academy-Frontend/  # Flutter client app (uses GetX for state management)
└── .github/                   # Organization-level configurations and templates
```

---

## Contributing

To contribute:

1. Fork the repository.
2. Create a new branch.
3. Submit a pull request with a description of your changes.
