# Klipper-KP5L-Configuration With 
Based on: ![nehilo/Klipper-KingRoon-Printers](https://github.com/nehilo/Klipper-KingRoon-Printers)
Acceleration configured for best quality.

If you use Armbian change serial to: /dev/serial/by-id/usb-1a86_USB_Serial-if00-port0

# Possible problems
MCU lost connection ater 20-40 minutes printing.
Kliper log: MCU Lost connection, 
Linux log: usb usb5-port1: disabled by hub (EMI?), re-enabling...
I had this problem on Orange Pi PC+ with Armbian. I change orane pi to laptop with Ubuntu and affter haven`t any problems.
