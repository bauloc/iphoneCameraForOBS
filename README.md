# IPHONE CAMERA FOR OBS

The app will turn your camera into a media input source for OBS and streamlab
The technique used is RTSP and streaming over the local network

## Step to run example:
1. Run this project with xcode, build to your iphone device
2. You will see **rtsp address** display on screen, enter it to VLC to test your connection.
3. Open OBS/Streamlab on computer, 
3.1 Source -> Ad(+) -> Media source
3.2 Untick option Local file
3.3 Enter your **iphone address** on field Input, address like: rtsp://192.168.2.67
4. Go live

![Screenshot](app_iphone_demo.png)
![Screenshot](obs_demo_1.png)
![Screenshot](vlc_demo_1.png)
