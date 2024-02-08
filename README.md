# Kafka Monitoring with Prometheus and Grafana

This project provides a solution to monitor Kafka clusters using Prometheus and Grafana.

## Requirements

- Docker
- Docker Compose

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/kayademirs/kafka_monitoring.git
    ```

2. Navigate to the project directory:

    ```bash
    cd kafka_monitoring
    ```

## Starting the Project

1. Start the project using Docker Compose:

    ```bash
    docker-compose up -d --build
    ```

    This command will start Prometheus and Grafana containers.

2. Open your browser and go to the Grafana interface:

    [http://localhost:3000](http://localhost:3000)

3. Log in to Grafana (default username: `admin`, password: `admin`).

4. Once logged in to Grafana, create dashboards to visualize metrics from Kafka using Prometheus data.

To stop and remove the Docker containers when the project is no longer in use, use the following command:

```bash
docker-compose down
```
