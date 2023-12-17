# Moleculer-ts

This is a [Moleculer](https://moleculer.services/)-based microservices project with typescript

-   Install Moleculer CLI

           npm i -g moleculer-cli

-   Generate Moleculer Project

          moleculer init project-typescript moleculer-typescript

-   Enabled And Disabled Microservice features

    -   Add API Gateway (moleculer-web) service? (Y/n) Y
    -   Add API Gateway (moleculer-web) service? Yes
    -   Would you like to communicate with other nodes? (Y/n) Y
    -   Would you like to communicate with other nodes? Yes
    -   Select a transporter (Use arrow keys)
    -   Select a transporter NATS (recommended)
    -   Would you like to use cache? (y/N) Y
    -   Would you like to use cache? Yes
    -   Select a cacher solution
    -   Select a cacher solution Redis
    -   Add DB sample service? (Y/n) Y
    -   Add DB sample service? Yes
    -   Would you like to enable metrics? (Y/n) Y
    -   Would you like to enable metrics? Yes
    -   Select a reporter solution (Use arrow keys)
    -   Select a reporter solution Prometheus
    -   Would you like to enable tracing? (Y/n) Y
    -   Would you like to enable tracing? Yes
    -   Select an exporter solution
    -   Select an exporter solution Zipkin
    -   Add Docker & Kubernetes sample files? (Y/n) Y
    -   Add Docker & Kubernetes sample files? Yes
    -   Use ESLint to lint your code? (Y/n) Y
    -   Use ESLint to lint your code? Yes
    -   reate 'moleculer-typescript' folder...
    -   Would you like to run 'npm install'? (Y/n) Y
    -   Would you like to run 'npm install'? Yes

## Run

        npm run dev

After starting, open the http://localhost:3000/ URL in your browser.

## NPM scripts

-   `npm run dev`: Start development mode (load all services locally with hot-reload & REPL)
-   `npm run start`: Start production mode (set `SERVICES` env variable to load certain services)
-   `npm run cli`: Start a CLI and connect to production. Don't forget to set production namespace with `--ns` argument in script
-   `npm run lint`: Run ESLint
-   `npm run ci`: Run continuous test mode with watching
-   `npm test`: Run tests & generate coverage report
-   `npm run dc:up`: Start the stack with Docker Compose
-   `npm run dc:down`: Stop the stack with Docker Compose
