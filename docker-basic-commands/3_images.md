## Task 1
List all the images available in local repository

`docker images`{{execute}}

## Task 2
Pull an image _busybox_ from docker hub

`docker pull busybox`{{execute}}

## Task 3
List the images again, busybox should be available

`docker images`{{execute}}

## Task 4
Delete the _busybox_ image

`docker rmi busybox`{{execute}}

You can also stop the container by it's ID also. 

`docker rmi ID`

ID doesn't need to be required to be complete. The first few unique characters are also enough as ID.
