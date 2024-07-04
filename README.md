# Movie Review Application

This repository contains the code for a movie review application developed as part of a full-stack development course. The application uses MongoDB for the database, Java and Spring Boot for the backend, and React for the frontend. 

## Project Setup

### Backend (Java and Spring Boot)

1. **JDK and IntelliJ IDEA Installation**
    - Ensure you have JDK installed. Download and install IntelliJ IDEA for your development environment.

2. **MongoDB Atlas**
    - Set up a MongoDB Atlas account and create a new cluster. Obtain the connection string for your database.

3. **Project Initialization**
    - Initialize your Spring Boot project using [Spring Initializr](https://start.spring.io/).

4. **Project Structure**
    - Follow the structure as outlined in the course for organizing your backend code.

5. **Running The Project**
    - Use IntelliJ IDEA to run your Spring Boot application.

6. **Writing The First Endpoint**
    - Implement your first REST endpoint and test it using Postman or a similar tool.

7. **Database Configuration**
    - Configure your application to connect to MongoDB using the connection string from MongoDB Atlas.

8. **Installing Additional Dependencies**
    - Install necessary dependencies for your Spring Boot application using `pom.xml`.

9. **Setting Up Environment Variables**
    - Store sensitive information like database connection strings in environment variables.

10. **Movies and Reviews Endpoints**
    - Create endpoints for managing movies and reviews.

11. **Testing**
    - Write tests for your endpoints to ensure they work correctly.

12. **Backend Conclusion**
    - Wrap up the backend development and ensure everything is working as expected.

### Frontend (React)

1. **Frontend Introduction**
    - Set up your development environment for React.

2. **Create the React Project**
    - Initialize a new React project using Create React App.

3. **Applying Bootstrap to our React application**
    - Install Bootstrap and integrate it into your React application for styling.

4. **Implementing the Use State and Use Effect Hooks**
    - Use React hooks for state management and side effects.

5. **Create Home and Hero Component**
    - Develop the Home and Hero components to display movie information.

6. **Style the Carousel**
    - Apply styling to the carousel component for a better user experience.

7. **Create Header Component (Navigation)**
    - Implement the header component for navigation.

8. **Create Trailer Component with react-player**
    - Use `react-player` to create a component for playing movie trailers.

9. **Create Movie Reviews Functionality**
    - Implement functionality for users to add and view movie reviews.

10. **Add and Get Reviews with HTTP Requests**
    - Use HTTP requests to interact with the backend for adding and retrieving reviews.

11. **Wrap Up**
    - Finalize the project and ensure everything is working correctly.

## Running the Project

### Backend

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/movie-review-app.git
    cd movie-review-app/backend
    ```

2. Set up environment variables:
    ```sh
    export MONGODB_URI=your_mongodb_connection_string
    export OTHER_ENV_VAR=value
    ```

3. Run the backend server:
    ```sh
    ./mvnw spring-boot:run
    ```

### Frontend

1. Navigate to the frontend directory:
    ```sh
    cd ../frontend
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Start the React development server:
    ```sh
    npm start
    ```

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

