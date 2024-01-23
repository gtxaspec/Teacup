# Teacup-Rev-C
Teacup T31 development board

Tested config as follows:

## Operating System: OpenIPC 

## Video: Camera sensor Sony IMX327 confirmed working with 15pin PiCam module. 
```https://www.amazon.com/dp/B085VLS96S```

To initialize the camera sensor on boot issue the following command.
```fw_setenv sensor imx327``` 
This will set the sensor in the uboot environment and start the sensor on boot 

## Networking:
```https://www.amazon.com/dp/B00MYT481C```

Asic USB 2.0 ethernet adapter. This adapter works in both uboot and userland.
GMAC PHY also pinned out to a header for use with an external phy.

## Audio
Audio out and Mic tested and work

