# property_monitor
An enterprise digital asset monitoring platform

# Backend

Backend is a Django-based network monitoring system with the following key features and configurations:

## Core Features
- TCP/IP monitoring with configurable timeout (5s), max latency (0.5s) and retry attempts (3)
- HTTP endpoint monitoring with 5s timeout
- Email testing functionality
- JWT authentication for API security
- PostgreSQL database backend
- Scheduled tasks using django-crontab:
  - TCP tests run every minute
  - Email account tests run daily at midnight

## Technical Stack
- Django 4.2
- Django REST Framework
- PostgreSQL Database
- Simple JWT for authentication
- django-crontab for scheduled tasks
- CORS enabled for cross-origin requests

## Apps
- cert: Certificate management
- tcp: TCP monitoring
- property: Property management  
- emailTest: Email testing
- setting: System settings
- end_point: Endpoint monitoring
