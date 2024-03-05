# Docker Example

This repository contains a Docker Compose setup for launching two Docker containers: one for a database and another as an entry point.
## Database description:
### example.db
schema:
      ```bash
      CREATE TABLE users(id INTEGER PRIMARY KEY, name TEXT, email TEXT); 

content:
      ```bash
      1|John|john@mail.ru
      2|Jane|jane@mail.ru

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/xclamation/Grid-task-1.git

2. Navigate to the project directory where docker-compose.yml is located:
   ```bash
   cd /project/directory

3. Build the Docker containers:
   ```bash
   docker-compose build

4. Start the Docker containers:
   ```bash
   docker-compose up

## Now you can see the data from the example.db in the terminal 
