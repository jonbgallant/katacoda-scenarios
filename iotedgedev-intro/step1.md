We have created a Docker image that contains all of the Azure IoT Edge Dependencies including: Python, Docker, .NET Core SDK and the Azure CLI.

Execute the following command to run the container.

> This will take a few minutes to complete.

`docker run -it -v /var/run/docker.sock:/var/run/docker.sock -v /root:/root -w /root jongallant/iotedgedev`{{execute}}
