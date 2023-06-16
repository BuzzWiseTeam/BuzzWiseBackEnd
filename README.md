<h1 align="center">Buzz Wise Back-End<h1>

<h2>Setup & Installation</h2>

<h3>Node.js & NPM</h3>

- Install all of the dependencies: `npm install`
- Run the project: `npm run dev | npm run start | npm run test`

<h3>Docker</h3> 

- Docker build: `sudo docker build -t buzz-wise-backend .`
- Docker run container: `sudo docker run -it -p 8080:8080 --name=buzzwisebackend buzz-wise-backend`
- Docker start: `sudo docker start buzzwisebackend`
- Docker Stop: `sudo docker stop buzzwisebackend`
- Docker remove: `sudo docker rm buzzwisebackend`

<h3>Google Cloud Platform (GCP) Services</h3>

- Cloud Run update service: `gcloud run services update buzzwisebackend --port 8080`
