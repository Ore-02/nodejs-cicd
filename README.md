# nodejs-cicd
This repository contains a simple Node.js app with a complete CI/CD GitHub Actions pipeline:
1. Tests the code with `npm test`.
2. Builds the Docker image.
3. Health-checks the image.
4. Pushes the image to Docker Hub.
5. Deploys the container to a remote server using SSH and Docker.
