## Task 1
List all the images available in local repository

`docker images`{{execute}}

## Task 2
List all the images

## Task 3
Run a container using the _redis_ image in background named redis

`docker run -d --name redis-app redis`{{execute}}

## Task 4
Check the running containers

`docker ps`{{execute}}


## Task 5
Stop the running container

`docker ps`{{execute}}

## Task 6
Stop the running container

`docker stop redis-app`{{execute}}

You can also stop the container by it's ID also. 

`docker stop ID`

ID doesn't need to be require to be complete. First few unique characters are also enough as ID

## Task 7
Check all the containers running and stopped.

`docker ps -a`{{execute}}

## Task 8

Remove just stopped container by _NAME_ or _ID_

`docker rm redis-app`{{execute}}
 