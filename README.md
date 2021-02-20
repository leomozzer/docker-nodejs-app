# Deploying Docker
This is a demo of an app that is deployed into a cloud computing service like AWS or Azure

## Rocketseat
https://www.youtube.com/watch?v=kqBCHYf_adA

For windows you need to run on git base
Requirements:
* docker
* docker-compose
* docker-machine https://docs.docker.com/machine/install-machine/

AWS commands:
* docker-machine --driver amazonec2 {MACHINE_NAME}
* eval $("C:\Users\USER_NAME\bin\docker-machine.exe" env {MACHINE_NAME)
* docker-compose up -d
* docker-machine kill {MACHINE_NAME}
* eval $(docker-machine env -u) -> to exit from the ec2 docker