# QuizApp Project

This project is a simple QuizApp that allows users to take quizzes on various topics. The application is containerized using Docker, making it easy to deploy and run on any system with Docker installed.

## Prerequisites

Before you begin, ensure that you have Docker installed on your machine. If you don't have Docker installed, you can download it from the [official Docker website](https://www.docker.com/).

## Project Structure

- **index.html**: The main HTML file for the QuizApp.
- **style.css**: The stylesheet containing the visual styles for the QuizApp.
- **app.js**: The JavaScript file that handles the logic and functionality of the QuizApp.
- **Dockerfile**: Defines the Docker image for the QuizApp.
- **docker-compose.yml**: Specifies the Docker Compose configuration for running the QuizApp.

## Getting Started

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/RishikeshOps/Quiz-App.git
2. Navigate to the project directory:
    ```bash
    cd Quiz-App
3. Run the application using Docker Compose:
    ```bash
    docker-compose up
This command will build the Docker image and start the QuizApp container.

## Access the QuizApp in your web browser:

Open your web browser and go to http://localhost:80 to use the QuizApp.

## Customization
Feel free to customize the QuizApp according to your preferences. You can modify the questions in the app.js file or adjust the styles in the style.css file.

## License
This project is licensed under the MIT License.