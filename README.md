Dockerized Full-Stack Web Application
This repository contains a Dockerized full-stack web application. It utilizes Docker to simplify the deployment process, allowing you to easily run the application on any system where Docker is installed.

Prerequisites
Before you begin, ensure you have the following installed on your machine: https://docs.docker.com/desktop/install/windows-install/

Docker: Follow the instructions here to install Docker on your system: 

Getting Started
To get started with this application, follow these steps:

1. Clone this repository to your local machine:

git clone https://github.com/lequyan2003/fullstack-flask.git

2. Navigate to the project directory:
cd your-repository

3. Build the Docker images:
docker compose build

4. Run the Docker containers:
docker compose up -d nextapp

5. Once the containers are up and running, you can access the application in your web browser at http://localhost:3000.

6. Stopping the Application
To stop the application and shut down the containers, simply press Ctrl + C in the terminal where the containers are running.

7. Configuration
You can customize the application configuration by modifying the environment variables in the .env file located in the root directory of the project.

Contributing
If you would like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/my-feature).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/my-feature).
Create a new Pull Request.

License
This project is licensed under the MIT License.

Acknowledgements
Thank you to Docker for providing a platform that simplifies application deployment.
