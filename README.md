# FlaskDemo
1) Created some random apis, simplistic using flask in python.
2) app is the name of the flask object
3) Dockerized the flask application using python:3.9-lim as the base image
4) Workdir is /app
5) all the required dependencies like gunicorn, flask etc are in requirements.txt
6) Using docker compose file to use multiple image/ contaienrs at the same time and make them interact with each other
7) Nginx image is used to act as the LoadBalancer when we further work with K8s in furure
8) COMMAND TO pull my images:
   **docker pull gauravraj2706/flaskproject:v1
     docker pull gauravraj2706/nginx:v1**
9) Command to filanny run the docker image:
    **docker-compose up --build -d**, you can also give a tag based on your needs  
