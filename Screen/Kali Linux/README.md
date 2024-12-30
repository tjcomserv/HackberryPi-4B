# Install Kali on your HackberryPi4B

You can download the image from [pi-imager](https://www.raspberrypi.com/software/)  
After you download and flash the image into the tf card, Copy and paste the following lines into the `/boot/config.txt`  

```sh
dtoverlay=vc4-kms-v3d
dtoverlay=vc4-kms-dpi-hyperpixel4sq
```

Insert the tf card and you can see HackberryPi running Kali linux

## Username and Password

Try 
```sh
kali
kali
```
Or
```sh
pi
pi
```

# Calibrate the Touchdisplay

Because desktop on Kali is running on x11, while other newer os lie RpiOS are updated to wayland, the touch can be handled differently on kali like the touch is inverted.
Follow the steps to do the calibration
