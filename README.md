# Raven - A Hospital Management Platform(In Progress)

Raven is a comprehensive Hospital Management Platform designed to streamline the management of hospital operations, patient records, and staff workflows. Built using Laravel, React, and PostgreSQL, this platform aims to enhance the efficiency and effectiveness of healthcare delivery.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [License](#license)

## Features

- **User Authentication**: Secure login and registration for hospital staff and administrators.
- **Patient Management**: Manage patient records, appointments, and medical history.
- **Staff Management**: Handle staff records, schedules, and roles.
- **Appointment Scheduling**: Easy appointment booking system for patients.
- **Inventory Management**: Track medical supplies and equipment.
- **Reporting**: Generate reports on various metrics for better decision-making.

## Technologies Used

- **Backend**:
  - Laravel (PHP Framework)
  - PostgreSQL (Database Management System)
- **Frontend**:
  - React (JavaScript Library)
  - Redux (State Management)
- **Others**:
  - Composer (Dependency Manager for PHP)
  - npm (Package Manager for JavaScript)
  - Git (Version Control)

## Installation

### Prerequisites

- PHP >= 8.0
- Composer
- Node.js >= 14
- npm
- PostgreSQL

### Steps

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/solobarine/raven.git
   cd raven
   ```

2. **Set Up the Backend API**:

   - Navigate to the API directory:

   ```bash
   cd api
   ```

   - Install the dependencies:

   ```bash
   composer install
   ```

   - Create a .env file and set up your database credentials:

   ```bash
   cp .env.example .env
   ```

   - Run the migrations to set up the database:

   ```bash
   php artisan migrate
   ```

   - Generate the application key:

   ```bash
   php artisan key:generate
   ```

3. **Set Up the Client**:

   - Navigate to the client directory:

   ```bash
   cd ../client
   ```

   - Install the dependencies:

   ```bash
   npm install
   ```

4. **Run the Applications**:

   - Start the API server:

   ```bash
   php artisan serve
   ```

   - Start the frontend server:

   ```bash
   npm start
   ```

5. **Access the Application**:

   Open your browser and go to http://localhost:3000 for the frontend and http://localhost:8000 for the backend API.

## Usage

Once the application is running, you can register as a user and explore the features provided by the hospital management platform. You can manage patient records, schedule appointments, and generate reports through the user-friendly interface.

## API Documentation

Detailed API documentation is available in the docs folder or you can access it via the Postman collection linked here: API Documentation.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
