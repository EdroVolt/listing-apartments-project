# Listing Apartments App Project

This is a full project for Listing Apartments App that contains 3 submodules (repos)

- [frontend](https://github.com/EdroVolt/listing-apartments-frontend)
- [Backend](https://github.com/EdroVolt/listing-apartments)
- [Mobile](https://github.com/EdroVolt/listing-apartments-mobile-app)


## Getting Started

To run this app locally using [Docker Compose](https://docs.docker.com/compose/)

- **first:** make sure you have [docker](https://docs.docker.com/get-docker/) and [docker-compose](https://docs.docker.com/compose/install/) installed on your machine.

- **Second:** Clone the repo

- **Third:** Open your terminal and make sure you are in the project root directory.

- **Forth:** Run the following command:

  ```bash
  docker-compose up --build
  ```

  > This command will run four containers, frontend, backend, Mongodb database, and mobile app.

You can access the web on [http://localhost:3000](http://localhost:3000)

You can access the backend on [http://localhost:8080](http://localhost:8080)

You can access the mobile on [http://localhost:8081](http://localhost:8081)
