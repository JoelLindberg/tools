# pingpong

A simple API for simple test cases.

Start: `venv/bin/uvicorn main:app --reload`

To build the Docker image, run the following command. Remember to replace your-dockerhub-username with your actual Docker

Hub username:
`docker build -t your-dockerhub-username/pingpong .`

To run the application in a Docker container:
`docker run -p 8000:8000 your-dockerhub-username/pingpong`

Once you have tested the image, you can push it to Docker Hub:
  1. Log in to Docker Hub: `docker login`
  2. Push the image: `docker push your-dockerhub-username/pingpong`
