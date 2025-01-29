# Php - Challenge "Login Screen"

## Description:
This PHP project implements a login screen that allows users to input their username and password. Upon submission, the system verifies the credentials against a RESTful API endpoint. If the credentials are correct, a popup dialog is displayed to welcome the user with their name. If the credentials are incorrect, a message indicating so is displayed, allowing the user to try again.

## Requirements:
1. **Login Screen Implementation:** Fields for username, password, and a submit button are implemented.
2. **Frontend Validation:** Frontend validation ensures that the username follows email format and the password field is not empty before submitting the form.
3. **Backend Validation:** Backend validation is implemented by sending a request to a RESTful API endpoint to verify the provided credentials.
4. **Git History:** Maintain a git history with clear commit messages.
5. **Clean Code:** Write clean code following SOLID principles.
6. **Artifacts:** Include artifacts demonstrating masterpiece coding, coding style, etc.
7. **Unit Tests:** Implement unit tests to ensure code reliability and functionality.

## Additional Points:
- **Authentication Tokens:** Authentication tokens are used to authenticate users after successful login. A token is generated on the server upon successful authentication and returned to the frontend. The frontend includes this token in subsequent requests to the API for authentication, serving as proof of the user's identity for accessing protected resources.
- **Authorization Header:** The frontend sends the authentication token in the Authorization header of each request to the API, ensuring that only authenticated users can access the API endpoints.
- **Rate Limiting:** Rate limiting is implemented on the API to prevent abuse and ensure fair usage. The number of requests that can be made within a certain time period is limited to mitigate potential security threats.
- **API Key or Client ID/Secret:** If applicable, API keys or client ID/secret pairs are used to authenticate the frontend application with the API, adding an additional layer of security by ensuring that only authorized applications can access the API.

## Deliverables:
- **Git Repository:** The project repository contains clear commit history and all necessary task files.
- **README File:** This documentation outlines the code structure, any design patterns used, and explanations for key decisions.
- **Additional Artifacts:** Any additional artifacts showcasing coding mastery, such as coding style guides or design patterns utilized.

## Notes:
- Ensure the login system is secure, preventing common vulnerabilities such as SQL injection or cross-site scripting (XSS).
- Follow best practices for PHP development and maintainability.
- Provide clear instructions for setting up and running the application and tests.
- Document any assumptions made during the development process.

Please refer to this README for detailed information about the project structure, implementation, and guidelines. If you have any questions or need further assistance, feel free to reach out.
