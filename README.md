# motiondetection
Motion Detection

https://www.pyimagesearch.com/2015/06/01/home-surveillance-and-motion-detection-with-the-raspberry-pi-python-and-opencv/

1. Necessario X11Forwarding per video
X11Forwarding 
http://blog.victormihalcea.com/2016/02/remote-desktop-raspberry-pi/

ssh -X pi

2. Set DropBox Account per salvataggio immagini

cd Documents/Progetti/opendata
source bin/activate
cd ../motiondetection
python pi_surveillance.py --conf conf.json

test camera
raspistill -v -o test.jpg

dopo il lancio del programma pi_surveillance.py da il seguente errore:
mmal: No data received from sensor. Check all connections, including the Sunny one on the camera board

https://www.pyimagesearch.com/2016/08/29/common-errors-using-the-raspberry-pi-camera-module/