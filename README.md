<!-- Please update value in the {}  -->

<h1 align="center">StudyHub-Backend</h1>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Overview](#overview)
  - [Built With](#built-with)
- [Architecture](#architecture)
- [Features](#features)
- [How To Use](#how-to-use)
  - [How to run the server with docker commands](#set-up-dev-environment)
    - [Backend](#backend)
- [Common Issues](#common-issues)

<!-- OVERVIEW -->

## Overview

StudyHub is an online tool that facilitates the development of efficient and productive study groups. It strives to bring together students who have similar study preferences, courses, and locations in order to improve collaborative learning experiences.


### Built With

<!-- This section should list any major frameworks that you built your project using. Here are a few examples.-->

- [Flask](https://flask.palletsprojects.com/en/2.2.x/)
- [PostgreSQL](https://www.postgresql.org/)
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/3.0.x/)
- [Flask-Restful](https://flask-restful.readthedocs.io/en/latest/)


## Architecture


## Features

<!-- List the features of your application or follow the template. Don't share the figma file here :) -->

- User Registration and Authentication: StudyHub provides a user-friendly registration process and secure authentication mechanism, allowing users to create accounts and access the platform securely.
![screenshot](https://ibb.co/vv8rTqq)
- User Profiles and Preferences: Users can create personalized profiles, including study preferences, courses, and availability schedules. This information is used to match users with compatible study groups.
- Study Group Matching Algorithm: StudyHub employs a neural network-based matching algorithm that analyzes user preferences and behavior to suggest the most suitable study groups. This algorithm ensures optimal group formations based on compatibility factors.
- Google OAuth 2.0 Integration: StudyHub integrates with Google OAuth 2.0 for seamless user authentication, enabling users to sign in using their Google accounts.
- Email Verification: To ensure the authenticity of user accounts, StudyHub incorporates email verification functionality. Users receive email notifications to verify their email addresses during the registration process.
- API Security: StudyHub implements API security best practices, including JWT tokens and bcrypt hashing, to protect sensitive user data and ensure secure communication between the client and server.
- Docker Containerization: The application is containerized using Docker, providing an isolated and portable environment for seamless deployment and scalability.
- AWS and GCP Integrations: StudyHub integrates with AWS services such as DynamoDB, Lambda, and SES for email delivery, along with GCP Geolocation API for address verification.
- Unit Testing: The codebase includes comprehensive unit tests for the REST APIs, ensuring functionality, reliability, and maintainability.


## How To Use

