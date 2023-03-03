# Tools used to record crash logs for iOS

There are several tools that can be used to record crash logs for iOS devices. One of the most commonly used tools is Apple's Xcode development environment, which includes a built-in crash log organizer.

- [ ] To use ***Xcode*** to view crash logs for an iOS device, you'll need to connect the device to your computer and select it as the target device in Xcode. Then, go to the "Window" menu and select "Devices and Simulators" to open the Devices window. In the Devices window, select your device, and then select the "Crash Logs" tab to view a list of crash logs for your device.
- [ ] Another tool that can be used to view crash logs for iOS devices is ***iTunes***. To view crash logs using iTunes, connect the device to your computer and select it in iTunes. Then, click the "View Device Logs" button in the "Device" section of the iTunes window.
- [ ] Finally, you can also use the iOS ***Console*** app to view crash logs for an iOS device. To do this, you'll need to install the app from the App Store and then connect the device to your computer using a USB cable. Once the device is connected, the iOS Console app will display a list of crash logs for the device.
- [ ] To access the logs on the physical iOS ***device*** go to *Settings > Privacy > Analytics and Improvements > Analytics Data*.

The retrieved logs may look undecipherable, becauase they are not symbolicated. Devs can [symbolicate](https://betterprogramming.pub/how-to-symbolicate-crash-logs-in-ios-b05637591364) the iOS crash logs before reading them.
