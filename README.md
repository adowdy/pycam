Collection of scripts playing around with rasberry pi camera

1. did raspberry pi config to turn on camera:
  sudo raspi-config
	Interfacing Options >
		Camera > Enable > REBOOT

2. use python3 module 
```python
#!/usr/bin/python3
from picamera import PiCamera
PiCamera().capture('/home/pi/Desktop/image.jpg')
```
  
