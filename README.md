# push-docker-image-dockerhub
creating container for python application and pushing to docker hub. 
Follow below steps
1) Keep ready your python application and docker file in GitHub
2) create ec2 with ubuntu
3) install docker using sudo(root user, by default docker has to be installed root user only)
   command and make sure it is up and running 
4) just verify to make sure your user has permissions  to run docker by running docker run hello-world.
   if not having permissions to your user , add your user to docker group 
5) if you changed permissions then make logout and log in back to reflect the permissions
6) Clone your application and docker file in GitHub into ec2 instance 
7) build docker image
8) verify docker image is created or not
9) then run the docker image
10) now push your docker image to docker hub

**My docker image on docker hub: docker pull satheeshovsn/my-python-app-image:latest**
