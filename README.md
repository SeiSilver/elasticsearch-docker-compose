# Elasticsearch with docker compose

## Getting Started

To run the code in local with Docker-Compose, please follow these steps:

### Prerequisites

Docker
Docker-Compose

### Installation

1. Clone the repository to your local machine.
2. Run
    ```shell
    docker-compose build
    ```

### Usage

1. Run the following command to start the containers in detached mode. This will start the application and its
   dependencies, such as databases or message queues:
    ```shell
    docker-compose up -d
    ```
2. You can verify that the application is running by navigating to http://localhost:5601/app/home in your web browser.

### Stopping

* If you want to stop the running containers, run the following command:
    ```shell
    docker-compose stop
    ```

### Removing Existing Docker-Compose

* If you want to remove the existing Docker-Compose and all its associated resources, run the following command:
    ```shell
    docker-compose down -v
    ```
