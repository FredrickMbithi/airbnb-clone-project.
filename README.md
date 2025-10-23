# Airbnb Clone Project

## Overview
Brief about project goals.

Team Roles
- Backend Developer: Handles API and logic.
- Database Admin: Designs and maintains DB.
- DevOps Engineer: Handles CI/CD pipelines.

## Technology Stack
- Django: Backend web framework for APIs.
- PostgreSQL: Relational database for storing user/property/booking data.
- GraphQL: API query language for flexible data fetching.
- Docker: For containerization.
- GitHub Actions: For CI/CD automation.

## Database Design
Entities:
- **User**: id, name, email, password.
- **Property**: id, title, price, location, owner_id.
- **Booking**: id, property_id, user_id, start_date, end_date.
- **Review**: id, property_id, user_id, rating, comment.
- **Payment**: id, booking_id, amount, status.

Relationships:
- One user can own multiple properties.
- A property can have many bookings and reviews.
- A booking has one payment.

## Feature Breakdown
- **User Management**: Sign up, login, logout.
- **Property Management**: Add, update, delete properties.
- **Booking System**: Users can book properties.
- **Payment Integration**: Secure payments.
- **Review System**: Users can review properties.

## API Security
- **Authentication**: JWT-based authentication for secure access.
- **Authorization**: Role-based access control.
- **Rate Limiting**: Prevent abuse.
- **Data Validation**: Ensure only valid input is processed.

## CI/CD Pipeline
- CI/CD pipelines ensure automatic testing and deployment.
- Tools: GitHub Actions, Docker.

