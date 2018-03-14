# Dockerimages
This repo purposes is to create/dockerize application into docker image. I'll add different type application to be dockerize from time to time

## Reason
The reason why I do this is to easily refresh the docker , kubernetes stuff when haven't touch them for a long time.
Hopefully, this can help people out there to refresh their mind about docker


# How to push to docker register
## Docker hub
Refer here : https://ropenscilabs.github.io/r-docker-tutorial/04-Dockerhub.html

## Google Cloud Registry
Refer here : https://cloud.google.com/container-registry/docs/pushing-and-pulling



# Docker Debug

## Run Image
$ docker run -p 49160:8080 -d <your username>/node-web-app

## Get Log
$ docker logs <container id>

Tail the log:
$ docker logs -f <container id>


# Kubernetes Deployment
Refer here : https://cloud.google.com/kubernetes-engine/docs/tutorials/hello-app


## Configure Domain Names with Static IP Address
https://cloud.google.com/kubernetes-engine/docs/tutorials/configuring-domain-name-static-ip

## Different TCP Network Load Balancer vs HTTP(S) Loan Balancer
https://cloud.google.com/kubernetes-engine/docs/tutorials/http-balancer#background 
