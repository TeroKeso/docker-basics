# Management layers for Docker


## Docker managaments tools GUI

Docker is easy to manage with CLI and Docker composer but it is not easy to manage with GUI. There are several GUI tools available to manage Docker containers. Some of the popular Docker GUI tools order of complexity are:
    * Vscode Docker Extension
    * Portainer
    * Rancher 

    Docker Extension to VScode is must have tool if you are connecting to remote docker host. It is very easy to use and has lost of features manage docker containers or visualization of now running configuration. Main missing features are history of containers and what is running on the container. Also host management is not available.

    Rancher is very complex and has lots of features. It is very good for large scale deployment and management. It is not suitable for small scale deployment. Main features is the integration with Kubernetes and other cloud providers.

### Portainer

Portainer is a lightweight management UI which allows you to easily manage your Docker host or Swarm cluster. Portainer is meant to be as simple to deploy as it is to use. It consists of a single container that can run on any Docker engine (Docker for Linux and Docker for Windows are supported). Portainer allows you to manage your Docker containers, images, volumes, networks and more ! It is compatible with the standalone Docker engine and with Docker Swarm.