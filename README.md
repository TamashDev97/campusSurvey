
# Campus Survey

CampusSurvey is a dynamic and scalable system designed for managing surveys efficiently. It uses modern technologies on both the frontend and backend to ensure a robust user experience. The backend is developed with Spring Boot using the Hexagonal Architecture (also known as ports and adapters), while the frontend employs React and Vanilla JavaScript.

The project enables the creation, management, and administration of complex surveys, including chapters, questions, and response options. Security and data integrity are ensured using Spring Security and comprehensive input validation.


## Features

- Survey Management:
    - Create, edit, and delete surveys.
    - Assign chapters to organize survey content.
    - Chapter and Question Management:
    - Organize questions within chapters.
    - Define various question types (text, multiple choice, etc.).
- Response Option Management:
    - Configure different options for multiple choice questions.
- Roles and Permissions:
    - Define and assign user roles to control access.
- User Interaction:
    - Friendly and responsive user interface for managing surveys.
- Security and Validation:
    - Robust security using Spring Security.
    - Centralized exception handling and validation to ensure data correctness.



## Technologies
- Backend
    - Spring Boot: Core framework for the backend.
    - Hexagonal Architecture: Ensures modularity and maintainability.
    - Spring Data JPA: Manages data persistence.
    - PostgreSQL / MySQL: Relational databases used for storing surveys, questions, responses, and users.
    - RESTful API: Enables communication between frontend and backend.
    - Spring Security: Provides authentication and authorization.
    - Exception Handling: Global exception handling for consistent error management.
- Frontend
    - React: Component-based library for building the user interface.
    - JavaScript Vanilla: Direct DOM manipulation for lightweight optimizations.
    - Axios: HTTP client for API requests.
    - Bootstrap / Tailwind CSS: For responsive and attractive UI design.
    - React Router: Handles navigation within the single-page application (SPA).

## Installation

- 1. Clone the repository:
    ```
    git clone https://github.com/your-repo/CampusSurvey.gi`
    ```

- 2. Backend Setup:
    - Navigate to the backend directory.
    - Ensure you have Java and Maven installed.
    - Build the project:
        ```
        mvn clean install
        ```
- 3. Frontend Setup:
    - Navigate to the frontend directory.
    - Ensure Node.js is installed.
    - Install dependencies:
        ```
        npm install
        ```
    - Start the frontend development server:
        ```
        npm start
        ```


## Usage/Examples
    - Login: Access the system by logging in with your credentials.
    - Create a Survey: Navigate to the "Manage Surveys" section and click "Create New Survey".
    - Add Chapters and Questions: After creating a survey, add chapters and questions using the intuitive interface.
    - Manage Response Options: For multiple choice questions, configure the available options.
    - Publish Surveys: Once ready, publish the survey to make it available for users.


