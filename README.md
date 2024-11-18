# MySQL Docker Compose Example

This repository provides a simple way to spin up a MySQL container with a preloaded database using Docker Compose.

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

### Steps to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/houstonlws/PBM-Database.git
   cd PBM-Database

   ```

2. Run Docker Compose:

   ```bash
   docker-compose up

   ```

3. Access the MySQL database:

   Host: localhost
   Port: 3307
   Username: user
   Password: 12345678
   Database: PBM-Database

4. To stop the containers, press `Ctrl+C` in the terminal or click stop in docker desktop.

5. To restart the container after stopping it, run the following command in the terminal where you ran `docker-compose up` command before stopping it:

```bash docker-compose start









```
