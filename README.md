# Klipper-KP5L-Configuration With 
Based on: https://github.com/nehilo/Klipper-KingRoon-Printers
Acceleration configured for best quality.

1. If you use Armbian change serial to: /dev/serial/by-id/usb-1a86_USB_Serial-if00-port0
2. Before use calibrate Z offset in KP5L/bltouch.cfg
3. If You haven`t BlTouch 
3.1 Comment Include in printer.cfg
3.2 Configurate [stepper_z] in KP5L/stepper.cfg 
4. Enjoy

# Possible problems
MCU lost connection ater 20-40 minutes printing.
Kliper log: MCU Lost connection, 
Linux log: usb usb5-port1: disabled by hub (EMI?), re-enabling...
I had this problem on Orange Pi PC+ with Armbian. I change orane pu to laptop with Ubuntu and affter haven`t any problems.
