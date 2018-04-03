# University of Minnesota NLP-ADAPT (Artifact Discovery and Preparation Toolkit)

## Experiments in creating Dockerized containers utilizing: 

Build Docker multi-container services using `docker-composr` to run NLP-TAB annotation browser and ElasticSearch engine.

From root directory issue command: `docker-compose up`

This will proceed to build images and run services associated with each Dockerfile as defined in the file `docker-compose.yml`.

NB: This example assumes `docker-compose.yml` is in the parent directory, and that there is a `Dockerfile` in each of the subdirectories, along with their dependencies (dependencies are not included: although an Ansible playbook to create these are in the works). 