# System Architecture

## 1. Frontend (Flutter)
The frontend of the application is developed using Flutter, which allows for cross-platform mobile application development. Key features include:
- **User Interface**: A responsive and intuitive UI designed for smooth navigation.
- **State Management**: Utilizes Provider for managing app state efficiently.
- **Network Calls**: Employs Dio for making API calls to the backend.

## 2. Backend (Python Flask)
The backend is built using Python's Flask framework. Key components include:
- **RESTful API Endpoints**: Each endpoint corresponds to a specific resource or action. 
- **Business Logic**: Handles the core functionality of the application such as form handling and database interactions.

## 3. APIs
- **OpenAI**: Used for generating responses and assisting users based on their inputs.
- **Firebase**: For real-time data storage and user authentication services.
- **Razorpay**: Handles payment processing.

## 4. Database Schema
- **Users Table**: Contains user information, authentication details.
- **Payments Table**: Stores transaction details including amount, user, status.
- **Data Collection Table**: Holds input data provided by users for processing and analysis.

## 5. Authentication Flow
1. User signs up using email and password.
2. User receives a verification email.
3. On clicking the verification link, their account is activated.
4. User logs in using credentials.

## 6. Data Flow Diagrams
- **User Input Flow**: Shows how user input is captured in the frontend, sent to backend, processed, and the response returned.
- **Payment Process Flow**: Illustrates how payment details are collected from the user, processed with Razorpay, and stored in the Payments table.

## Conclusion
This architecture describes the essential components of the ResumeAI system, detailing how each part interacts to create a cohesive application.