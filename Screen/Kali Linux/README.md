# Install Kali on your HackberryPi4B

You can download the image from [pi-imager](https://www.raspberrypi.com/software/)  
After you download and flash the image into the tf card, Copy and paste the following lines into the `/boot/config.txt`  

```sh
dtoverlay=vc4-kms-v3d
dtoverlay=vc4-kms-dpi-hyperpixel4sq
```

