MagTek Credit Card Reader in Linux
==================================

This code was written for MagTek USB Swipe Readers part numbers are 21040101, 
21040102, 21040103, 21040104, 21040113, 21040114, 21040119, 21040139, and 
21040143. You can find this part number on the bottom of the device.

Read a complete description of this example program on 
[my blog](http://www.micahcarrick.com/credit-card-reader-pyusb.html)

May 2023 - modify Micah's example to work with Elo Edge Connect in HID mode

Setup a virtual environment and install PyUSB

    python3 -m venv venv
    source ./venv/bin/activate
    pip install PyUSB

I'm just testing the reader and don't have udev setup so run as root

    sudo bash
    source ./venv/bin/activate
    python magtek-pyusb.py

