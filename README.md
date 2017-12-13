# faas-docker

## Setting up local environment: ##
Run:
```
./script/server
```

OpenFaaS Portal is then accessible at faas.dev if vagrant-hostsupdater plugin is installed for Vagrant:

http://faas.dev:8080/ui/

## Background ##
For setting up Docker Swarm, forked an existing solution from:

https://github.com/mrlesmithjr/vagrant-ansible-docker-swarm

https://github.com/tooming/vagrant-ansible-docker-swarm

Then tweaked the vagrant-ansible-docker-swarm solution for adding openfaas/faas from:

https://github.com/openfaas/faas

Finished tutorial about openfaas-cli and tested out pushing a Docker image to Docker Hub:

https://blog.alexellis.io/quickstart-openfaas-cli/

https://hub.docker.com/r/tooming/callme/

Next steps would have been:
* Create a Docker image for handling requests

* Deploy the handler with openfaas-cli into Docker Swarm
