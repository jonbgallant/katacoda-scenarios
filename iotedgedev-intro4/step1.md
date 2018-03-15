To get started, let's run a custom **Azure IoT Edge Dev Container** that contains all of the pre-requisites required for IoT Edge development, including: 
- Docker
- .NET Core SDK
- Python
- Pip
- Azure CLI

Click the following to run the container:

`docker run -it -v /var/run/docker.sock:/var/run/docker.sock -v /home:/home -w /home/iotedge jongallant/iotedgedev`{{execute}}

This container also includes the Azure IoT Edge Dev Tool, which was installed via pip with the following command: 

`pip install -U azure-iot-edge-dev-tool`

(You do not need to execute this command because it is already included in the container)


## Continue
Click the **Continue** button when you see the `/home/iotedge` folder in the terminal to the right.
