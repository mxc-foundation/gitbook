# 💡 LED status of your NEO device

The NEO device has various LED lights that indicate its status. When the device is first powered on, the LED will slowly blink blue (500ms on/500ms off) to indicate that the system is initializing.

As the device boots up, the LED will transition to a slow blinking yellow (500ms on/500ms off) to indicate that it's checking for a local network and internet connection. Once the device successfully connects to the internet, the LED will turn steady yellow to indicate that it's connecting to a supernode.

After connecting to the supernode, the LED will transition to a slow blinking yellow/green (1000ms green/1000ms yellow) to indicate that it's connecting to the LoRa network. Once everything is connected, the LED will turn steady green to indicate that the device is fully operational.

If the device is unable to connect to the local network, the LED will turn steady red to indicate that there is no connection.

If the device is in configuration mode, the LED will fast blink cyan (100ms on/100ms off) to indicate that it's waiting for confirmation to reset data.

If a system upgrade is in progress, the LED will turn purple to indicate that the device is in the upgrade process and should not be powered off.

It's important to note that the LED statuses may differ depending on the specific model of your NEO device. Be sure to consult your device's manual for specific details on its LED status indicators.

By understanding the LED status of your NEO device, you can quickly identify and troubleshoot any issues that may arise during its operation.

<figure><img src="../../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>
