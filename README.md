# Dockerized WordPress Development Environment

This project provides a Dockerized environment for WordPress development, complete with WordPress, MySQL, and phpMyAdmin services.

## Getting Started

These instructions will guide you on how to get this project up and running on your local machine for development purposes.

### Prerequisites

Before you begin, make sure you have installed:

- [Git](https://git-scm.com/downloads)
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Clone the Repository

First, fork the repository to your GitHub account. Then, clone the forked repository to your local machine using the following command in your terminal:

```bash
git clone https://github.com/Enadabuzaid/wp-local-with-docker
```


### Navigate to the project directory:
```bash
cd wp-local-with-docker
```

### Configure Environment Variables
Copy the .env.example file to a new file called .env:
```bash
cp .env.example .env
```

Open the .env file with your favorite text editor and modify the environment variables to match your desired configuration.


### Start the Docker Containers
Run the following command to start the Docker containers:
```bash
docker-compose up -d
```


This will build and start the ```WordPress```, ```MySQL```, and ```phpMyAdmin``` containers.

#### Access WordPress

Once the Docker containers are up and running, you can access the WordPress site by navigating to http://localhost:8000 in your web browser.

#### Access phpMyAdmin

You can manage your database using phpMyAdmin by navigating to http://localhost:8080 in your web browser.
