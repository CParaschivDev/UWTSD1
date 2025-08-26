---
services: app-service\web,app-service
platforms: python
author: cephalin
---

# UWTSD Student Registration System

This is a student registration application for the University of Wales Trinity Saint David (UWTSD). The application allows students to register for events and provides an interface to view all registered attendees.

The application is built with Python Flask and connects to a PostgreSQL database via SQLAlchemy.

## Features

- Student registration with name and email
- View list of all registered students/attendees
- Confirmation page after successful registration
- PostgreSQL database storage with SQLAlchemy ORM
- Responsive web interface using Bootstrap

## Technical Details

The database connection information is specified via environment variables `DBHOST`, `DBPASS`, `DBUSER`, and `DBNAME`. This app always uses the default PostgreSQL port.

## Deployment

The application is configured for deployment to Azure App Service with automated CI/CD via GitHub Actions.

# Contributing

This project follows standard open source contribution practices. Please ensure all contributions align with the university's guidelines and policies.