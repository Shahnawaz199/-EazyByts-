# -EazyByts-

# CRM System

## Overview
This project is a Customer Relationship Management (CRM) system developed to manage customer data efficiently. The application uses **JavaScript** for frontend logic and **Firebase** for backend services like authentication and data storage.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Firebase Realtime Database / Firestore
- **Authentication**: Firebase Authentication

## Firebase Services
- **Firebase Authentication**: Used to manage user login and security.
- **Firebase Realtime Database / Firestore**: Used to store customer-related information like names, contact details, interactions, and more.
- **Firebase Hosting**: Deployed on Firebase Hosting for efficient, fast, and secure delivery of the application.

## Data Storage
Customer data is stored in Firebase's **Firestore** (or **Realtime Database**) in collections. Each document represents a customer, containing fields such as:
- Name
- Email
- Phone number
- Interaction history

## Setup Instructions
1. Clone the repository to your local machine.
2. Install the Firebase CLI by running:
   ```
   npm install -g firebase-tools
   ```
3. Set up Firebase in your local environment using:
   ```
   firebase init
   ```
4. Link the project to your Firebase account by providing your Firebase configuration details (API key, project ID, etc.).

## Precautions
When using this application, consider the following security measures:
- **Authentication**: Always ensure users are authenticated before allowing access to customer data.
- **Data Validation**: Properly validate data before writing to Firebase to prevent incorrect or malicious data entries.
- **Sensitive Data**: Do not store sensitive information like passwords or personal identifiable information (PII) in plaintext.
- **Access Control**: Use Firebase rules to restrict access to the database based on user roles.

## License
This project is licensed under the MIT License.

