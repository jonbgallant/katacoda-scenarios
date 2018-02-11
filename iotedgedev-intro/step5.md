Each module in your IoT Edge solution needs built and packaged up into an image and sent to the Azure IoT Edge runtime.

The `modules --build` command will dotnet restore, build, publish and then docker build, tag and push each module it finds in your solution. In this case, it will find the filtermodule. If you have more modules in the modules folder the IoT Edge Dev Tool will automatically discover them and do the same process for each of them.

The `modules --deploy` command will take the dynamically generated `.config/deployment.json`{{open}} file and deploy it to your edge device. 

`iotedgedev modules --build --deploy`{{execute}}

Click Continue when you see the `DEPLOY COMPLETE` message.
