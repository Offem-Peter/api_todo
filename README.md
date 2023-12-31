# API for Managing TODOs

Managing Todos

#### Dependencies

- `docker`
- `node`
- `npm`

#### How to run locally

- Clone this repo
- Use `env.sample` as a guide to set up your local env as `env.local`
- On your local terminal, run `docker-compose --env-file .env.local up`. This will set up all the containers and download the images if you don't have them already. This might take a few minutes.

#### Running Tests

- Keep your docker containers running and open a second terminal
- On terminal run `docker exec -ti todo /bin/sh` (replace `todo` with your container name, use `docker ps` to see container names )
- Inside the container, run `npm run test` to ensure all tests are passing
