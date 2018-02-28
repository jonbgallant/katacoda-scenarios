Each module in your IoT Edge solution needs built and packaged up into an image to be pulled from the Azure IoT Edge runtime.

For each module in your Edge Solution, the `modules --build` command will:
1. dotnet build and publish
1. docker build, tag and push to a container registry. 

The `modules --deploy` command will deploy the modules to your edge device.

Click on the following to execute those commands.

`iotedgedev modules --build --deploy`{{execute}}

Click Continue when you see the `DEPLOY COMPLETE` message.
