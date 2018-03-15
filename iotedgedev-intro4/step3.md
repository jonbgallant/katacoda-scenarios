Each module in your IoT Edge solution needs to be built and packaged into a Docker image to be pulled from the Azure IoT Edge runtime.

## Build Command
The `build` command will do the following for each module in your solution:

1. dotnet build and publish
1. docker build, tag and push to a container registry. 

Click on the following to execute the `build` command:

`iotedgedev build`{{execute}}

## Deploy Command
The `deploy` command will deploy the module and route configuration to your edge device.

Click on the following to execute the `deploy` command:

`iotedgedev deploy`{{execute}}


## Build and Deploy
You can also run both of these commands at the same time with: `iotedgedev build --deploy`

## Continue
Click the **Continue** button below when you see the `DEPLOY COMPLETE` message.
