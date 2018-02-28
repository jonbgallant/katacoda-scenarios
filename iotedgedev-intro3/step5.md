We now have messages flowing from the simulated temperature sensor module, to the filter module, to the EdgeHub and then up to IoT Hub.  Let's see those messages now:

Click on the following command to view the messages flowing to IoT Hub from our IoT Edge device.

`iotedgedev iothub --monitor-events`{{execute}}

> Please be patient as you wait for messages to appear in the terminal as it takes a few moments for the Edge Runtime to load the modules.

Click Summary after you see the messages printed in the terminal.
