Now we'll run the `init` command to create an Azure IoT Edge Solution and setup our Azure IoT Hub and Edge Device.

`iotedgedev init`{{execute}}

You will be asked to open a browser and go to https://aka.ms/devicelogin and enter a code. You will then need to login to your Azure account. Complete that process and then come back here.

The Azure IoT Edge Dev Tool is driven by Environment Variables. The only two variables required to get started are IOTHUB_CONNECTION_STRING and DEVICE_CONNECTION_STRING.  The `init` command will retrieve those settings and automattically save them to your solution's `.env` file.

Click Continue
