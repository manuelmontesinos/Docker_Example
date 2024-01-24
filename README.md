# A Sample Application using Docker Containers

This repository contains the files to run the Python program [BProbit_Car.py](BProbit_Car.py) using Docker containers. The instructions to use them are provided below.

## Building and running your application

When you're ready, start your application by running:
`docker compose up --build`.

Your application will be available at http://localhost:8000.

## Deploying your application to the cloud

First, build your image, e.g.: `docker build -t myapp .`.
If your cloud uses a different CPU architecture than your development
machine (e.g., you are on a Mac M1 and your cloud provider is amd64),
you'll want to build the image for that platform, e.g.:
`docker build --platform=linux/amd64 -t myapp .`.

Then, push it to your registry, e.g. `docker push myregistry.com/myapp`.

Consult Docker's [getting started](https://docs.docker.com/go/get-started-sharing/)
docs for more detail on building and pushing.

## References
* [Docker's Python guide](https://docs.docker.com/language/python/)
* [Overview of Docker Desktop](https://docs.docker.com/desktop/)
* [Python programs from "Quantitative Economics", by Manuel V. Montesinos](https://github.com/manuelmontesinos/quant_econ)