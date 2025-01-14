# property_monitor
This is an enterprise-grade monitoring system designed for real-time network and digital asset management. Built using a Django backend with a Vue frontend, the platform ensures efficient monitoring, management, and notification functionalities for IT environments.

Backend is a Django-based network monitoring system with the following key features and configurations:

## Core Features

The application includes the following main modules:

1. **Endpoint Monitoring** - Endpoint overview and monitoring
2. **Network Management** - Network latency analysis and property management
3. **Authentication Management** - Certificate management functionality
4. **Mail System** - Email notification management
5. **System Settings** - Security configuration and system settings

# Technical Stack

## Backend
- Framework: Django 4.2 with Django REST Framework.
- Database: PostgreSQL.
- Authentication: Simple JWT.
- Task Scheduling: django-crontab for scheduled jobs.
- Cross-Origin Requests: CORS enabled for seamless integrations.

## Frontend
- Framework: Vue 3 with Composition API.
- UI Components: Element Plus.
- Other Dependencies:
  - @fortawesome/fontawesome: Icon library.
  - date-fns: Utility for date manipulation.
  - ajv: JSON schema validation.

## Apps
- cert: Certificate management
- tcp: TCP monitoring
- property: Property management  
- emailTest: Email testing
- setting: System settings
- end_point: Endpoint monitoring

### Login Page
![image](https://github.com/xuemian168/property_monitor/blob/main/img/login.jpg)

### Dashboard
![image](https://github.com/xuemian168/property_monitor/blob/main/img/monitor.jpg)

### Property
![image](https://github.com/xuemian168/property_monitor/blob/main/img/properties.jpg)

### Certifications
![image](https://github.com/xuemian168/property_monitor/blob/main/img/certs.jpg)

### Certification Detail
![image](https://github.com/xuemian168/property_monitor/blob/main/img/cert.jpg)

### End Points
![image](https://github.com/xuemian168/property_monitor/blob/main/img/end1.jpg)

### Settings
![image](https://github.com/xuemian168/property_monitor/blob/main/img/settings.jpg)

### Mail System Monitor
![image](https://github.com/xuemian168/property_monitor/blob/main/img/mails.jpg)
