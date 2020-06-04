# Kaggle_Container
This is the docker setup for Jupyter notebook/lab for Kaggle using gcr.io/kaggle-images/python

### Steps to setup the docker container:

1. Clone the repo
2. Go to the folder where Dockerfile is located 
3. $ docker-compose build
4. It may take a while to pull the image (15.6GB for latest one)
5. Create/Start the container using below command
6. $ docker-compose up
7. Stop the container using the below command
8. $ docker-compose down

#### port can be specified in docker-compose.yml
##### in this case port 8892 is used

#### Run the jupyter notebook from http://localhost:8892/tree
