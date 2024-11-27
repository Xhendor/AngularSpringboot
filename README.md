# Start the Spring Boot backend:
- cd backend
- ./mvnw clean install
- ./mvnw spring-boot:run

# Start the Angular frontend:
- cd backend/src/resources/statc
- ng serve
- Open your browser to http://localhost:4200

# The system provides:

- User registration with email, username, and password
- Secure login with JWT authentication
- Protected dashboard route
- Automatic token management
- Form validation
- Error handling
- Modern UI with responsive design

# To test the system:

- Navigate to http://localhost:4200/register
- Create a new account
- Log in with your credentials
- You'll be redirected to the dashboard
- Try accessing the dashboard directly - you'll be redirected to login if not authenticated
- Use the logout button to end your session

