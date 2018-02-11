The Azure IoT Edge Dev Tool is driven by Environment Variables. The only two variables required to start are IOTHUB_CONNECTION_STRING and DEVICE_CONNECTION_STRING.  When the Edge Dev Tool runs it loads all the variables in the `.env` file, so we need to place those two variables there before we run further commands. The Edge Dev Tool has an `azure --setup` command to help you retrieve those settings and store them in the solution's `.env` file.

Click on the following command to start that process:

`iotedgedev azure --setup`{{execute}}

You will be asked to open a browser and go to https://aka.ms/devicelogin and enter a code. You will then need to login to your Azure account. Complete that process and then come back here.

When you come back to the terminal you will see your Azure subscriptions.  You'll select the appropriate subscription, create or select and IoT Hub and then create or select and Edge Device.

After the IoT Hub and Device are selected, the connection strings will be printing in the terminal and it will prompt you to save the connection strings to your `.env` file.  Enter `y` and then hit click enter to do that.

Then, click the following command to see the `.env` file with your connection strings.

`iotedge/.env`{{open}}

Click Continue after you have verified that the `.env` file contains your connection strings.


