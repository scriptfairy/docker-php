# docker-php
Create a Docker image with php and apache.

1- Download Docker for Mac and install from https://docs.docker.com/docker-for-mac/install/

2- Type the following from the command line to download docker image php:5.6-apache
<pre>
docker run php:5.6-apache
</pre>

3- You can browse the docker repo for PHP at https://hub.docker.com/_/php/

4- Since we don't need to create a new image, therefore we don't need to create Dockerfile. Dockerfile is only needed if we need to create a new image based on the image we download.

5- run the following

<pre>
chmod +x start
chmod +x stop
</pre>


