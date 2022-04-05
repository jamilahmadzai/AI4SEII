# How to set up the environment
* Below are the steps which explain the whole process of setting up the environment in details

## Download docker image
* First of all you have to install docker to run this environment.
* Then you have to pull the image command ’docker pull jamildocker1/aihub:v2’.
* In this case jamildocker1 is the username of dockerhub where docker image is stored.
* aihub is the name of docker image which you will pull and which contians the execution environment. 
* FInally v2 is the name of tag for current docker image. 
* You can see from following figure how you can pull it using PowerShell.
<img src="https://github.com/jamilahmadzai/AI4SEII/blob/main/images/pulldock.jpg" alt='pic1'/>

## Run docker image
* After the pull is complete you will see the docker image in your docker/image section as you can in the following figure. 
* Simply open docker, go to images on the left side of docker there you will see the pulled image.
* Once you have docker image locally in your docker then you simply have to run the image. 

* Once you click on the run button shown in above figure a small screen will appear in docker as you can see from following figure. 

* As right now this server runs on local port so you have to assign port number as well as you have to specify the name of container. 
* Once you have assigned both the port number and container name you can click on run button to start the image inside the container you hava assigned.
* Once you click on ’run’ button the container will execute at port number which you have assigned in previous step. 
* Go to containers section in your docker and you will see that the container is running like in following figure. 
* 
* On the right end of the name of container you will find certain buttons for running and stopping the container on the given server, deleting the container, opening the command line interface and a button for opening the given container in browser.

## Run the server
* Now docker container is up and running, the only thing that remians is to run jupyterhub on that server. 
* Once you run jupyterhub the user will be able to use the execution environment.
* For this step you have to open ’command line interface’ as discussed in previous step. 
* Once command line interface is open you have to run the bash command in order to enter the root of the container you are working on because you can only run and use it once you are inside the container.
* Once you are in the root of docker container now you can simply run jupyterHub by entering command ’jupyterhub’ inside the container. 
* After that you will be able to see your server hase started running on the given server. You can see it from following figure.

## Create User
* Now the server is ready and running. You can use this environment for your AI application development purposes. 
* Open the server in browser and you will see jupyterhub screen for signup. 
* Enter username and password. For admin you have to keep the username as admin and for other users you can give whatever name you want to give. 
* Once you have signed up, you can then sign in with the credentials you have entered.
* For creating other users once you enter your username and password for signing the request will be forwarded to admin and user will only be able to access the
execution environment once the request is approved by admin.
* Once admin has approved the user, now they have access to all the libraries, files and other features of the system. 
* Now the user does not need to install libraries which are already installed and provided by this execution environment. 
* User can access all the libraries and tools to create their own AI applications.
