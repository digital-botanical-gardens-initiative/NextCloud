# NextCloud instance

This repository contains a Docker Compose setup for a NextCloud instance for the EMI sample handling. This setup is temporary (longer term solution is beeing built at https://github.com/earth-metabolome-initiative/emi-monorepo). To get started, follow the instructions below.

## Prerequisites

Before you begin, make sure you have the following prerequisites installed:

- Docker: [Install Docker](https://docs.docker.com/get-docker/)
- Docker Compose: [Install Docker Compose](https://docs.docker.com/compose/install/)

## Setup

### 1. Clone the repository to your local machine:

```bash
git https://github.com/digital-botanical-gardens-initiative/NextCloud.git
cd NextCloud
```

### 2. Create a .env file in the root folder and edit it to suit your needs:
```bash
cp .env.example .env
vim .env
```

### 3. Deploy the application:

```sh
docker compose up -d
```

This command will start the necessary services, including the database and your application.

## Accessing Your Application

Once the deployment is complete, you can access your application by opening a web browser and navigating to http://localhost:8080.


## Stopping and Cleaning Up

To stop the application and remove the containers, run the following command:

```sh
docker compose down
```

## Contributing

If you would like to contribute to this project or report issues, please follow our contribution guidelines.

## License

see [LICENSE](https://github.com/digital-botanical-gardens-initiative/NextCloud/LICENSE) for details.