# Janitri Backend Assignment  

This is a Spring Boot backend project for managing users, patients, and heart rate data.

## Features  
- User Registration & Login  
- Patient Management  
- Heart Rate Data Handling  
- RESTful APIs  
- Data Validation & Exception Handling  

## API Endpoints  
### *User APIs*  
- POST /users/register - Register a new user  
- POST /users/login - Login with email and password  

### *Patient APIs*  
- POST /patients/add - Add a patient  
- GET /patients - Retrieve all patients  

### *Heart Rate APIs*  
- POST /heart-rate/record - Record heart rate  
- GET /heart-rate/{patientId} - Retrieve heart rate data  

## Setup Instructions  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/janitri-backend.git
