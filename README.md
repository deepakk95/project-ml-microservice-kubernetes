# Operationalize-a-Machine-Learning-Microservice-API

![CircleCI](https://dl.circleci.com/status-badge/img/gh/deepakk95/project-ml-microservice-kubernetes/tree/master.svg?style=svg)

## Project OverView
Deploy a  Python flask application that serves predictions about housing prices through API calls. It uses a a pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features such as average rooms in a home and data about highway access, teacher-to-pupil ratios and so on.

### Project Tasks
Test your project code using linting
Complete a Dockerfile to containerize this application
Deploy your containerized application using Docker and make a prediction
Improve the log statements in the source code for this application
Configure Kubernetes and create a Kubernetes cluster
Deploy a container using Kubernetes and make a prediction
Upload a complete Github repo with CircleCI to indicate that your code has been tested

## Instructions
1. clone the project repository, and navigate to the project folder
```
git clone https://github.com/udacity/DevOps_Microservices.git
cd DevOps_Microservices/project-ml-microservice-kubernetes
```
2. Create (and activate) a new environment, named .devops with Python 3. If prompted to proceed with the install (Proceed [y]/n) type y.
```
python3 -m venv ~/.devops
source ~/.devops/bin/activate
```
3. Run `make install` to install the dependencies
4. Install other dependencies like - hadolint, docker and kubernetes (minikube)
5. Run app.py in docker using `./run_docker.sh`
6. Run app.py in kubernetes using `./run_kubernetes.sh`
7. Upload docker image to dockerhub using `./upload_docker.sh`
