We now want to setup and start the Edge Runtime so that we can download the images from our container and start sending messages to IoT Hub.

The `runtime --setup` command will apply the `.config/runtime.json`{{open}} file to the runtime. This file has everything you need to start the runtime, including paths to the EdgeAgent image and container registry credentials.

The `runtime --start` command will start the Azure IoT Edge runtime, which will retrieve the latest configuration that was deployed in the last step and start the process of downloading and running modules.

Click on the following command to setup and start the IoT Edge Runtime.

`iotedgedev runtime --setup --start`{{execute}}

Click Continue after you see the `RUNTIME STARTED` message.
