# CRM System: Project Overview and Ongoing Development

## Project Overview

The CRM System is designed to streamline customer relationship management, which integrates a robust frontend, backend, and database to manage various customer-related activities, including profile management, purchase tracking, license validation, notifications, and more. This repository documents the processes, tools, and technologies used to build and maintain the system, highlighting my role in its successful implementation.

## My Responsibilities

I am building the system from scratch and responsible for the entire development lifecycle, including:

-	Requirements Engineering: Gathered and refined stakeholders’ needs to define clear system requirements.
-	Database Design: Creating and managing the database schema using AWS RDS and PostgreSQL.
-	Backend API Development: Designing and implementing RESTful APIs using Python, Django rest framework.
-	DevOps and Deployment: Managing deployment on AWS, including CI/CD pipelines.
-	Future Enhancements: Continuously planning and implementing new features to improve the system.

## Projects
### DevOps and Cloud Services
- Backend: Auto Scaling Group, Elastic Load Balancer, EC2
- Frontend: AWS S3, Cloudfront
- Database: AWS RDS
- CI/CD Pipeline: CodePipeline for production and development enviroments, with automated testing and deployment
- Logging: Centralize logs using CloudWatch Logs.
- Email Service: AWS SES
- File Storage: AWS S3
- Domain Management: AWS Route53

### Backend Development
- Authentication: Utilized JWT for user authorization and SHA256 for API key generation to support license validation.
- CRUD APIs: Enable customers to view data such as profiles, purchases, licenses, warranties, and notifications, while allowing staff users to view and edit this information.
- License Validation: Enables the system to verify license status upon receiving API requests from a user’s Radisen product, ensuring licenses are active and within usage limits for medical image inference.
- Notifications: Designed an asynchronous system to send email notifications for new product announcements, purchase updates, and more. Users can customize their notification settings to choose the type of updates they receive.

## Ongoing Work
- API Gateway: Setting up Amazon API Gateway to support blue/green deployments for seamless updates and minimal downtime.
- Issue Platform: Developing a system where customers can report issues or requests, automatically notifying the relevant parties.

## Future Features
- Q/A Chat: Implement a chat interface for real-time customer support interactions.
- Payment System: Integrate payment gateways for secure transactions.

