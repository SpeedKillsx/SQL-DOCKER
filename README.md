# SQL DOCKER
Welcome to the SQL Docker repository! This repository contains Docker images for various SQL databases, including MySQL, PostgreSQL, and SQLite. These images are designed to be easy to use and configure, allowing you to quickly set up a local development environment for your SQL projects.

## Getting Started
To get started with the SQL Docker images, follow these steps:
1. Clone this repository to your local machine:
   ```bash
   git clone <repository-url>
   ```
2. Build the Docker image:
    ```bash
     docker-compose up --build -d
     ```
3. Connect to the SQL database using your MySQL account credentials:
    ```bash
     docker exec -it my-sql-container bash
     ```
4. Once inside the container, you can access the MySQL command line interface using the following command:
    ```bash
     mysql -u root -p
     ```


## Directory Structure
This repository contains the following directories for each SQL database:
- `scripts/`: Contains SQL scripts for creating tables and inserting data.