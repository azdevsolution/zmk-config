Flashing, Firmware, and Bootloaders#
One of the great things about the nice!nano is how easy it is to flash the device. To jump into the bootloader all you need to do is double tap reset. You can do this by either double tapping your reset button on your keyboard, or you can double tap RST and GND pins on the nice!nano quickly with tweezers.

Once you are into the bootloader, connect your nice!nano via USB to your computer if you haven't already. Your nice!nano should now show up in your OS as a USB storage device named "NICENANO".

Flashing is now as easy as copying a .uf2 firmware file to the storage device. You can do this by copying in the terminal, dragging and dropping it in your file explorer, or however else you copy files to a storage device in your OS.

Now you may be wondering how to get one of these mystical .uf2 files. You get them by building one of the firmwares available. Checkout the Wireless Firmware page to get information on how to configure and build a few different types of firmwares along with some recommendations.

The bootloader the nice!nano uses is the Adafruit nRF52 Bootloader. You can read more about its features, updating the bootloader, and using DFU to flash firmware on its GitHub.
