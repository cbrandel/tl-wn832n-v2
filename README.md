# Driver for tp-link TL-WN832N v2 usb wifi dongle
Built from sources provided by tp-link:

- Download Page: http://www.tp-link.de/download/TL-WN823N.html#Driver
- File: http://static.tp-link.com/res/down/soft/TL-WN823N(EU)_V2_160315_Linux.zip

Patches applied have been found on the net:
- https://bugs.launchpad.net/ubuntu/+source/broadcom-sta/+bug/1504975
- https://github.com/hadess/rtl8723bs/issues/24
- https://github.com/donahue95/rtl8192eu-linux-driver/issues/2

Successfully compiled under debian jessie

Successfully loaded on a PI 3 with the kernel raspberrypi-kernel_1.20160921-1
