# Healthcare Assistance App

This is the backend for the Healthcare Assistance App, which connects patients in need with donors who want to provide financial support. The backend is built with Django REST Framework and uses PostgreSQL as the database. It includes a User Management System (UMS) to handle registration, authentication, and authorization of users.

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Setup and Installation](#setup-and-installation)
- [Environment Variables](#environment-variables)
- [Database Migrations](#database-migrations)
- [Running the Server](#running-the-server)
- [API Endpoints](#api-endpoints)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Features

- User registration and authentication (including email verification)
- Hospital, doctor, patient, and donor management
- Patient request submission and approval
- Secure donation transactions
- Admin panel for managing users and hospitals
- Token-based authentication for secure API access

## Technology Stack

- **Backend Framework**: Django, Django REST Framework
- **Database**: PostgreSQL
- **Authentication**: Django Allauth, Django REST Auth
- **API Documentation**: Django REST Swagger or DRF-YASG

## Setup and Installation

### Prerequisites

- Python 3.8+
- PostgreSQL
- pip (Python package installer)

### Installation Steps

1. **Clone the repository:**

   ```bash
   https://github.com/AbdulAbdullah/Healthcare-Assistance.git
   cd healthcare-assistance-app
