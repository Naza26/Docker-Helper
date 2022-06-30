# Docker-Helper

#### *What is Docker?*

Docker is an open plattform used to develop and execute different applications.

Docker enables us to separate the infrastructure from an application so we can develop faster and we can shorten the distance between development and production.

#### *What´s the difference between Docker and a Virtual Machine?*

- A virtual Machine emulates an infrastructure, while Docker emulate the operative system where applications run.
- Docker has a lighter visualization technology since it does not emulate infrastructure.
- Docker is focused on the environment required by the applications and not by the physical means of them.
- Virtual Machines have specific designated resources and they are not allowed to share it. On the other hand, Docker engine is able to distribute resources as needed depending on the demand of the containers.

#### *What are Images?*

Images are the "original" of the application we want to run.

We can create our own custom images based of an initial image.

See link attached: https://hub.docker.com/


#### *What are Containers?*

A container allows us to run an instance of an application without the need of downloading that application.

Containers are thought to be discarded. They are closed and isolated from everything.


#### *Docker most used commands: *

- pull --> Downloads an Image
- push --> Uploads an Image
- ps --> Lists Conatiners
- run --> Runs an Image in a Container
- stop --> Stops the execution of a Container
- exec --> Executes a command in a Container
- rm --> Deletes a Container
- build --> Creates an Image based of a DockerFile

#### *What is a DockerFile?*

- Based of a DockerFile our image will be created
- It allows us to customize the application we want to run
- We start from an initial image and we start adding what we need to
- Some reserved words are: FROM, RUN, COPY, WORKDIR, EXPOSE

#### *What are Volumes and Ports?*

- These two allow our containers to not be isolated from everything
- Volumes provide us with storage from outside of our container
- Ports allow us to connect with the container

#### *What is Docker Compose?*

It is a tool used to define and create several containers.

It allows us to to simplify the execution of containers that need to be working at the same time.

We need to create a file **docker-compose.yml** that will simplify and group our commands.




Notes taken were based from ppts extracted from Departamento de Computacion FIUBA and also from the Twitch meeting.

