# K8S react dockerization

Sandbox react app with dockerization

# Run

- `npm install` to install dependencies
- `npm start` to run it locally on port 3000

# Docker

- `docker build . -t docker-react` to build the docker image
- `docker images` to check the 'docker-react' image is in the list
- `docker run -p 3000:3000 -d docker-react` to run the container

You just need to open `http://localhost:3000/` to make sure the app is up and running.
