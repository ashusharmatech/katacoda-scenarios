## Task 1
Run a container using the _redis_ image

`docker run redis`{{execute}}

## Task 2
Stop the container using Ctrl+C

## Task 3
Run a container using the _redis_ image in background named _redis-app_

`docker run -d --name redis-app redis`{{execute}}

## Task 4
Check the running containers

`docker ps`{{execute}}

## Task 5
Stop the running container

`docker stop redis-app`{{execute}}

You can also stop the container by it's ID also. 

`docker stop ID`

ID doesn't need to be required to be complete. The first few unique characters are also enough as ID

## Task 6
Check all the containers running and stopped.

`docker ps -a`{{execute}}

## Task 7

Remove just stopped container by _NAME_ or _ID_

`docker rm redis-app`{{execute}}
 