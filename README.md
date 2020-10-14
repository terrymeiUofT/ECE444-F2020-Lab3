Tianchang Mei

This repo is a clone of https://github.com/miguelgrinberg/flasky


### Lab 4 Deliverable 2

##### How to build the system
After cloning this repo, open terminal and navigate to /ECE444-F2020-Lab3/activity2 folder, and run the following command:
```
docker build -t lab4_5:latest .
```

##### How to start the system (Method 1: docker run)
After a successful build, run the following command in the same directory as above to start the system:
```
docker run -d -p 5000:5000 lab4_5
```

##### How to start the system (Method 2: docker compose)
Alternatively, one could navigate to /ECE444-F2020-Lab3 folder, and run the following command to start the system:
```
docker-compose up
```

##### Screenshot of docker run command
![alt text][img2-1]

[img2-1]: https://github.com/terrymeiUofT/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/activity2/docker_run.jpg "screenshot of docker run command"

##### Screenshot of browser
![alt text][img2-2]

[img2-2]: https://github.com/terrymeiUofT/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/activity2/browser.jpg "screenshot of browser"

##### Screenshot of docker image
![alt text][img2-3]

[img2-3]: https://github.com/terrymeiUofT/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/activity2/docker_image.jpg "screenshot of docker image"


### Lab 4 Deliverable 3
Difference between Docker and Virtual Machine:
1. Docker stores code and its dependencies in a portable container, whereas Virtual Machine stores code and its dependencies on a specific machine that allows remote access.
2. The code and its dependencies stored in a Docker Image is not mutable, providing consistency and giving confidence to programmers that their code would work on any machine that provides Docker. On the other hand, anyone who has access to the virtual machine would be able to change the code and its dependencies.
