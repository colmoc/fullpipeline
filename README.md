Name: Colm O'Conchuir
Project 4
containerize and deploy a machine learning application using Kubernetes

To run:
./kubernetes_run.sh

Repo:
https://github.com/colmoc/k8smicroservicesapp.git

File descriptions:
Makefile - to setup project dependencies
requirements.txt - list of dependencies
Dockerfile - image definition
app.py - prediction application
run_docker.sh - to build and run app on image
make_prediction.sh - send sample json curl to app
upload_docker.sh - uploads img to dockerhub
run_kubernetes.sh - deploy container to k8 cluster

    output_txt_files/
        project output files
            - docker_out.txt
            - kubernetes_out.txt

circleci status badge
[![CircleCI](https://dl.circleci.com/status-badge/img/gh/colmoc/k8smicroservicesapp/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/colmoc/k8smicroservicesapp/tree/master)
