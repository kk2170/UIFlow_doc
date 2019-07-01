# Update firmware
_________________________________

><img src="/image/base/windows_logo.png" width="100" height="100" />
### For Windows

* __Downloading the driver__

>Go to[m5stack.com](http://m5stack.com/)and download the driver for your OS[CP210X driver](http://m5stack.com/download/Driver/CP210x_VCP_Windows.zip)
>![Download](/image/base/CP210X_DL.gif )

* __Installing the driver__

> Extract the zip file and run the install package in the extracted folder
>![install](/image/base/CP210X_install.gif )

—————————————————————————————————

* __Download M5Burner__

>Go to[flow.m5stack.com](http://flow.m5stack.com/)and click the gear in the top right corner. From the settings panel choose the M5burner for your system[M5Burner tool](http://flow.m5stack.com/download/M5Burner-flow-only.zip)
>![Download](/image/base/Burner_DL.gif )

* __Burning process__

> Extract the burner package and double click on the M5 Burner icon. Connect your M5Stack device and select its COM port from the list (Check Windows device manager if you are unsure of your COM port).Select the recommended baud rate 921600 and then select the firmware you wish to flash. Now press the burn button, your firmware will have flashed successfully once you see the message "leaving staying in bootloader". Reset your device to see the new firmware.
>![User](/image/base/Burner_user.gif )

### For Mac

* __Downloading the driver__

>Go to[m5stack.com](http://m5stack.com/)and download the driver for your OS[CP210X driver](http://m5stack.com/download/Driver/CP210x_VCP_Windows.zip)
>![Download](/image/base/CP210X_DL.gif )

* __Installing the driver__

> Extract the dmg file and run the install package in the extracted folder

* __Download M5Burner__

>Go to[flow.m5stack.com](http://flow.m5stack.com/)and click the gear in the top right corner. From the settings panel choose the M5burner for your system[M5Burner tool](http://flow.m5stack.com/download/M5Burner_MacOS.zip)
>![Download](/image/base/Burner_DL.gif )

* __Burning process__

>Click on the downloaded burner file to open it. The burner should auto detect the serial port your M5 Device is plugged into. Select your desired firmware and hit burn. Once the circle has completed your firmware will have completed flashing.

* __Mac Burner Troubleshooting__

>You may get a message on opening the mac burner saying it is damaged. This is not the case, it is just an issue with your OS blocking un-certified software. This issue will be resolved soon, However in the meantime you'll have to use this workaround. Open up the terminal Applications>utilities>terminal and type sudo spctl --master-disable. Now you'lll be able to use the burner. We reccommend you turn the app security back on after you have completed flashing your device. Open the terminal again but this time type sudo spctl --master-enable