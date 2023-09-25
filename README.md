# 3DO 4K USB CAMERA

The 3DO USB Camera is a compact USB camera based on the IMX485 sensor, designed for use with 3D printers.
This repository contains reference designs, additional resources may be found on printables.com or similar platforms.

<img src="./images/3DO-WEBCAMERA.png "  width="50%">

|                         | 4K (Sony IMX258)     |
|-------------------------|----------------------|
| Sensor Size             | 1/3.06               |
| Mega-Pixel              | 13MP                 |
| Frame Rate              | 30FPS@4K 60FPS@1080P |
| Lens type*              | Auto Focus          |
| FoV                     | 120Deg                |
| FPC length              | 5cm                 |
| Operating temperature** | -20°C TO 60°C        |
| Storage temperature     | -40°C TO 80°C        |


## Folders
- printers  printers (mounts for different printers)
- hardware (similar to [3DO Nozzle camera](https://github.com/3DO-EU/nozzle-camera/tree/main/hardware))

## Pinout
PCB uses a 5P 1.0mm pitch connector.
| Pin No. | Function	 | Color		      |
|---------|--------------|--------------------|
| 1       | USB 5VDC     | Red		          |
| 2       | Data -       | White		      |
| 3       | Data +       | Green		      |
| 4       | USB -VDC/GND | Black		      |
| 5       | GND/Shield   | Black (heat shrink)|

Wire no. 5 is an optional shield/drain wire, tho it will work without we recommend installing it.

<img src="./images/pinout_5p.png "  width="35%" align="left">
<img src="./images/pinout_usb2.png "  width="40%">
</br> 


## Software
The camera works as a standard UVC web camera and is therefore compatible with Linux, Windows, and Mac.
For streaming, we recommend using [mainsail](https://github.com/mainsail-crew/mainsail) + [crowsnest](https://github.com/mainsail-crew/crowsnest). 

## FAQ
- Does it work in an enclosed printer?

Yes, tho our camera is rated at 60C we have been running it for 48hrs in a 70C industrial heat chamber without any issues.

-  Can I bend/fold the FPC to make it shorter?

Yes, FPC is flexible and can be bent, if you want to fold it (180deg) we recommend doing this max one time in the same spot, or else you risk braking the lanes inside FPC.

Example of folding FPC

<img src="./images/FPC_BEND.jpg "  width="20%">

## Where to buy
EU / UK

<a alt="3DO" href="https://3do.eu/"><img src="https://3do.dk/img/logo-1694603603.jpg" width="200" ></a>

USA 

<a alt="Fabreeko" href="https://www.fabreeko.com/"><img src="https://cdn.shopify.com/s/files/1/0266/5001/7990/files/Fabreeko_Logo_ecf1536e-3074-4a0e-9306-87ca89f1abbd_320x.png" width="200" ></a>

<a alt="KB3D" href="https://kb-3d.com/"><img src="https://kb-3d.com/store/img/kb-3d-logo-1673465361.jpg" width="200" ></a>