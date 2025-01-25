# Bicycle Project

## Description
This is the source code for a Bicycle ecommerce application. Currently the webpage is using Django 
frameworks running on localhost. Media storage is hosted from an Amazon S3 Bucket.

Complete implementation and infrastructure will make use of an EC2 instance within a VPC. Static media 
will continue to be hosted on Amazon S3 where CORS is enabled. MySQL supports backend database which 
will be moved to an Amazon RDS database for persistant storage and durability. Finally, the application
will be deployed using Amazon Elastic Beanstalk, this ensures easy deployment, montioring, and scaling.

Best used with Python3.11

## Technologies Used
- Django
- MySQL
- AWS S3
- [Other technologies listed in description]

## Setup Instructions
1. Clone the repository
2. Create a virtual environment
3. Install dependencies: `pip install -r requirements.txt`
4. Create a .env file with required environment variables
5. Run migrations: `python manage.py migrate`
6. Start the server: `python manage.py runserver`

## Environment Variables Required
- DJANGO_SECRET_KEY
- DB_NAME
- ALLOWED_HOSTS
- CSRF_TRUSTED_ORIGINS
- DB_USER
- DB_PASSWORD
- DB_HOST
- DB_PORT
- AWS_STORAGE_BUCKET_NAME
- AWS_S3_REGION_NAME

## Features
- Allows user to choose bicycle parts for purchase
- Review order history
- Change banner color of logo
- Find locations/services 

