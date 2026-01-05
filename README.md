# Employee Management Dashboard

A React-based employee management system with authentication, CRUD operations, and search functionality.

## Overview

This application allows users to manage employee records with features including add, edit, delete, search, and filter operations. The dashboard displays employee statistics and provides a clean interface for employee data management.

## Tech Stack

- React.js
- JavaScript
- Tailwind CSS
- Lucide React (icons)
- Local Storage (data persistence)

## Features

- User authentication with login page
- Add new employees with profile image upload
- Edit existing employee details
- Delete employees with confirmation
- Search employees by name
- Filter by gender and active status
- View employee statistics
- Print employee list
- Responsive design

## Installation

Clone the repository and install dependencies:

```bash
npm install
```

## Running the Application

Start the development server:

```bash
npm start
```

The application will open at `http://localhost:3000`

## Login Credentials

- Username: admin
- Password: admin123

## Project Structure

```
src/
  - App.js (main component with authentication)
  - LoginPage component
  - Dashboard component
  - EmployeeForm component
```

## Employee Form Fields

- Full Name (required)
- Gender (required)
- Date of Birth (required, age 18-100)
- Profile Image
- State (dropdown with Indian states)
- Active/Inactive status

## Design Decisions

**Storage**: Used localStorage for simplicity and to avoid backend setup. Employee data persists across sessions.

**Authentication**: Implemented basic mock authentication. In production, this would be replaced with a proper backend API.

**Form Validation**: Added client-side validation for required fields and age constraints.

**Image Upload**: Images are converted to base64 and stored in localStorage for easy implementation.

**State Management**: Used React hooks (useState, useEffect) for managing application state.

**Filtering**: All filters (search, gender, status) work together to provide combined filtering results.



