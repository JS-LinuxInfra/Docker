# Docker
Containerized Application Deployment with Docker

## Scope
This project completed the following operational tasks. Screenshots are provided for each task completed, as well as the syntax used and why this task was executed.

## Tasks

### Determine the number of images on the host.
![Step1](images/step1.jpg)

### Determine the version of Docker running on the host.
![Step2](images/step2.jpg)

### Pull images from Docker Hub and confirm now on the host.
![Step3](images/step3.jpg)

### Start the container in the background, validate it is running, stop the container, validated it has stopped.
![Step4](images/step4.jpg)

### Validate containers running on the host, remove them, then validate they are no longer running or on the host.
![Step5](images/step5.jpg)

### Validate images on the the host, remove an image, confirm it is no longer on the host.
![Step6](images/step6.jpg)

### Start a container with the desired name, confirm it is now running on the host.
![Step7](images/step7.jpg)

### Start a container, pull from Docker Hub, map to desired ports, attach "blue" tag to container name.
![Step8](images/step8.jpg)

### Building a smaller image using the lite flag to reduce space used on the host.
![Step9](images/step9.jpg)

### Built my first image.
![Step10](images/step10.jpg)

### Determining the base operating system used by the python image.
![Step11](images/step11.jpg)

### Inspect this Dockerfile prior to containerizing it.
![Step12](images/step12.jpg)

### Run container, send to background and define the ports (-dp).
![Step13](images/step13.jpg)

### Run container of newly built image after mapping ports and sending to the background (-dp), confirm running on the host.
![Step14](images/step14.jpg)

### Inspect container config and determining the defined color.
![Step15](images/step15.jpg)

### Pull the ENVVAR from Docker Hub and set the password, deploy the DB with the defined ENVVAR and database name.
![Step16](images/step16.jpg)

### Launch the container, send to background, set the name, map the ports, define the environment variable, specify the image to use.
![Step17](images/step17.jpg)

### Determine the CMD variable defined in the Docker-wordpress Dockerfile.
![Step18](images/step18.jpg)

### Determine the CMD run when the Ubuntu container is run from the image.
![Step19](images/step19.jpg)

### Determine the ENTRYPOINT from the mysql Dockerfile.
![Step20](images/step20.jpg)

### Run the Ubuntu container in the background and pass the sleep 1000 seconds command to it while launching, validate it isnow up and running.
![Step21](images/step21.jpg)

### Create Dockerfile using compose in YAML.
![Step22](images/step22.jpg)

### Create the container, name it, send to background (-d), specify and name the image used, confirm running.
![Step23](images/step23.jpg)

### Create the container, name it, assign the ports (-p), link to another container and specify the image used.
![Step24](images/step24.jpg)

### Run docker-compose against the YAML file I created, send to the background, then confirm the container is running.
![Step25](images/step25.jpg)

### Stop containers, remove them, then confirm no longer running or present on the host.
![Step26](images/step26.jpg)

### Create a container, name it and assign to the none network.
![Step27](images/step27.jpg)

### Create a container, send to the background (-d), define the password ENVVAR, assign to a network, specify the image to run and confirm it is now running. 
![Step28](images/step28.jpg)

### Define password variable, run container in the background calling defined variable (password), sending to the background (-de), then confirm running.
![Step29](images/step29.jpg)

### Determine networks on the host.
![Step30](images/step30.jpg)

### Determine network details for the container.
![Step31](images/step31.jpg)

### Determine the subnet assigned to the bridge network.
![Step32](images/step32.jpg)

### Run container, map the volume to be used for data storage, send to the background, call the pre-defined ENVVAR, set image used, then confirm running.
![Step33](images/step33.jpg)

### Run container, send to the background, set both ENVVAR, the name and assign ports, assign to network, link to desired container and assign image to be used (-edp). Confirm running after starting.
![Step34](images/step34.jpg)

### Start container: create private registry, send to the background & map ports (-dp), set restart to always, name the registry and map the desired image.
![Step35](images/step35.jpg)

### Prune all containers without an image assigned to them.
![Step36](images/step36.jpg)

### Pull image from Docker Hub, assign desired tags and push to Docker Hub.
![Step37](images/step37.jpg)

### Remove last container from the host, confirm there are not any more running.
![Step38](images/step38.jpg)
