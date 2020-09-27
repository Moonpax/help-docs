# Dockers cmd

#### Visualizing Docker Containers and Images

http://merrigrove.blogspot.com/2015/10/visualizing-docker-containers-and-images.html

---

### Build Docker

`docker build . -t bpr_go_autocomplete-full`

## Run locally

`docker run -p 2005:8080 bpr_go_autocomplete`

#### save docker to file for production

`docker save -o c:/main/go-sample-app-multi.tar go-sample-app-multi`

#### docker load from file

`docker load -i go-sample-app-multi.tar`

#### show all images

`docker images -a`

#### show running images

`docker ps -a`

#### delete image

`docker rmi fc147ac57ebc`

#### delete all

`docker system prune -a -f`

#### run docker - delete when stop

`docker run -it --rm -p 5000:80 --name aspnetcore_sample aspnetapp`

#### run docker

`docker run -d -p 3070:3070 --name geocachems_test geocachems`

#### see files inside docker

`sudo docker exec -it geocachems_prod bash`

#### run docker

`docker run -d -p 3060:3060 --rm --name fltms_prod ftlms`

#### see docker network

`docker network`

#### help

`docker --help`

#### Run docker on ubuntu

`sudo su`

`ls`

`cd gobepro/docker/`

`ls`

`/home/ubuntu/gobepro/docker# ls`

`docker load -i bpr_go_autocomplete.tar`

`docker image ls`

`docker kill [id]`

`docker run -d -p 2005:8080 bpr_go_autocomplete`

`docker ps`

`telnet localhost 2005`

`docker logs fe8d6d651102`
