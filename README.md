# Henshin & Hate Speech

## Overview

"Henshin & Hate Speech" is an innovative project aimed at transforming hate speech in political discourse into constructive communication. Utilizing a web-based application, this project leverages advanced AI technologies, including pose and sound detection, to identify and modify hate speech in real-time. This approach not only highlights the project's commitment to addressing social issues through technology but also offers a platform for public engagement and critique.

## Features

Data Collection & Analysis: Harness web scraping to collect hate speech data, employing Machine Learning and NLP techniques for detection and analysis.

Interactive Web Application: Showcases the transformed speech via video, speech, and audience interaction in a user-friendly interface.

AI-Powered Transformation: Utilizes GANs, CNNs, and NLP for real-time speech and pose detection, content generation, and sentiment analysis.

Inclusive & Ethical Framework: Aimed at fostering positive political discourse, emphasizing the responsible use of AI.

## Getting Started

To experience "Henshin & Hate Speech," run the application locally:


### 1. Running the Docker Image

Follow these steps to run the Docker image:

1. **Install Docker**: If you haven't installed Docker, you can download it from [Docker's official website](https://www.docker.com/products/docker-desktop). Follow the instructions for your operating system.

2. **Pull the Docker image**: You can pull the Docker image from Docker Hub using the following command in your terminal:

    ```bash
    docker pull asliilhan/henshin-voices
    ```

3. **Run the Docker image**: After pulling the image, you can run it with the following command:

    ```bash
    docker run -p 5000:5000 asliilhan/henshin-voices
    ```

    This command will start the Docker container and map port 5000 inside the container to port 5000 on your host machine.

4. **Access the application**: Once the Docker container is running, you can access the application by opening your web browser and navigating to `http://localhost:5000`.

Please note that if port 5000 is already in use on your machine, you'll need to use a different port. You can do this by changing the `-p` option in the `docker run` command. For example, to use port 5001, you would use `-p 5001:5000`.

### 2. Clone repository to run the application locally:

Follow these steps to run the app locally:

1. **Clone Repository**: copy the command line and paste onto bash.

  ```bash
  git clone https://github.com/22036435/henshin-Voices.git
  ```
After the repository is cloned, navigate into the file.

2. **Install dependencies**:

  ```bash
  pip install -r requirements.txt
  ```

3. **Run app on localhost**: paste the line on bash and run. Once the App is running, you can access the application by opening your web browser and navigating to provided link.

  ```bash
  python app.py
  ```

### Prerequisites

Internet connection to access the web app.

Webcam acces to intreact.

No installation required for web-based interaction.

## Development Timeline

A detailed timeline from idea generation through to project completion, highlighting key development phases such as pose detection, model training, and web app development.

## Key Components

Data Collection: Utilizing web scraping and collaborations with Turkish journalists to gather relevant datasets. Scrapping [Turkish Parliamentary website](https://henshin-aslico-14859966a7ba.herokuapp.com) and running NLP model on the official reports.

AI Models: Development of various models for pose detection, speech transformation, and sentiment analysis.

Web Application: Implementation of a Flask backend with a user-friendly interface for real-time interaction.

##Testing & Deployment

Testing: Rigorous testing phases to ensure accuracy in pose detection, hate speech detection, and user interaction.

Deployment: The project is hosted on Heroku, providing easy access to users for real-time engagement.

## Acknowledgements

This project represents the culmination of my MSc Data Science and AI studies, embodying a practical application of my academic pursuits to tackle real-world issues through technology.
