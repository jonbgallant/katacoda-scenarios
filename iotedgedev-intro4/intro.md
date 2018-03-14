In this course, we'll learn the high-level **Azure IoT Edge** concepts and learn how to use the **Azure IoT Edge Dev Tool**.

**Azure IoT Edge** addresses two main scenarios:
1. **Gateway:** Enables non-internet connected devices to interact with Azure.
1. **Intelligence:** Enables local storage, compute and real-time decision making on the edge of your network.

If you are new to Azure IoT Edge, then you should read through the [Azure IoT Edge Concepts](https://docs.microsoft.com/en-us/azure/iot-edge/iot-edge-modules). In a nutshell, the Azure IoT Edge runtime is based on containers. The runtime itself is a container called EdgeAgent. IoT Edge also provides a container, called EdgeHub, that sends messages from the IoT Edge device to your IoT Hub. You, the developer, create custom modules, package them into containers and deploy them to the IoT Edge device via the IoT Hub. One of the biggest benefits of using the IoT Edge Runtime, is that you can remotely deploy new modules, adjust properties, and even remotely call methods on the IoT Edge Device.

The **Azure IoT Edge Dev Tool** assists developers in creating IoT Edge Solutions, coding and deploying modules and creating CI/CD pipelines. This CLI tool complements the [IoT Edge VS Code extension](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.azure-iot-edge) by turning multi-step manual processes into simple one-line commands, such as `iotedgedev build --deploy`, which performs all of the following for each module: dotnet restore, build, publish, docker build, tag, push and then deploys the configuration to the IoT Edge device.  You can find all of the details on Azure IoT Edge Dev Tool [here](https://aka.ms/iotedgedev).

We'll now walk through the IoT Edge Dev Tool Quickstart:

1. Start the IoT Edge Container 
1. Initialize an IoT Edge Solution and setup our Azure IoT Hub and Edge Device 
1. Build and Deploy our IoT Edge Modules
1. Setup and Start the IoT Edge Runtime 
1. Monitor Messages flowing from the IoT Edge Device to IoT Hub

Click the **Start Scenario** button to get started.
