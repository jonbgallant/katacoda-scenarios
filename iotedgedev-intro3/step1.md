To get started, let's run a custom **Azure IoT Edge Dev Container** that contains all of the pre-requisites required for IoT Edge development, including: 
- Docker
- .NET Core SDK
- Python
- Pip
- Azure CLI.

Click on the command below to run the `jongallant/iotedgedev` container, which will run the command in the terminal to the right.

When you see the following message printed in the terminal the container has been downloaded and you are safe to click the `docker run` command below. `Status: Downloaded newer image for jongallant/iotedgedev:latest`

`docker run -it -v /var/run/docker.sock:/var/run/docker.sock -v /home:/home -w /home jongallant/iotedgedev`{{execute}}

This container also includes the Azure IoT Edge Dev Tool, which was installed via pip with the following command: 

`pip install -U azure-iot-edge-dev-tool`

(You do not need to execute this command because it is already included in the container)

Click Continue 
