To get started, let's run a custom **Azure IoT Edge Dev Container** that contains all of the pre-requisites required for IoT Edge development, including: Docker, .NET Core SDK, Python, Pip, and the Azure CLI.

Click on the command below to run the `jongallant/iotedgedev` container, which will run the command in the terminal to the right.

When you see the following message printed in the terminal the container has been downloaded and you are safe to click the `docker run` command below. `Status: Downloaded newer image for jongallant/iotedgedev:latest`

`docker run -it -v /var/run/docker.sock:/var/run/docker.sock -v /root:/root -w /root jongallant/iotedgedev`{{execute}}

Click Continue 
