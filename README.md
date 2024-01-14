# OpenCV on Raspberry Pi
## Development environment
- Raspberry Pi CM4
- Raspberry Pi OS - Bullseye/Bookworm
- OpenCV 4.5.1
- Picamera2
- IMX219
- [boot/config.txt](https://github.com/atsss/RPi_configs/blob/main/bookworm/imx219.txt)

## Docs
- OpenCV official document
> https://docs.opencv.org/4.5.1/d2/de6/tutorial_py_setup_in_ubuntu.html
- Picamera2 official document
> https://datasheets.raspberrypi.com/camera/picamera2-manual.pdf
- [Medium notes](https://medium.com/p/4d9f7d60a3f2)

## How to install
1. Clone this repository and move the directory
2. Install OpenCV and Picamera2
```
chmod +x installer.sh
bash installer.sh
```
3. Test
```
cd scripts && python test_picamera.py
```

## Pretrained models
- Install from OpenCV
> https://github.com/opencv/opencv/tree/5.x/data/haarcascades
