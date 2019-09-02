# Memory Wipe Demo

Some Tibbo BASIC projects save data to device memory; then, when you upload another project, the data is still there. Or perhaps you want to upload the *same*project again, but test your setting initialization code. In other words, you want the device to be wiped clean before you upload your project, so you can see what your code does on a brand-new device.

This is what this little project does. Run it on your device, and it will simply wipe the EEPROM squeaky clean, filling it up with zeros. It starts up with the red LED on, and once it's done initializing the memory, it switches the green LED on instead. Then you can load your other project and run it as if it's on a brand-new device.