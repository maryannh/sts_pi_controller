# STS-Pi controller

A super simple web app controller for the Pimoroni STS-Pi robot, using Flask and Skeleton. The original has been updated to use symbols instead of words on the controller, and camera on/off buttons have been added.

## Pre-requisities
Boot up your Pi and either connect to it with monitor/keyboard/mouse, or with [VNC or SSH](https://www.raspberrypi.org/documentation/remote-access/).

If you haven't gone straight into Terminal, cick on the icon as shown below:

![screen](https://raw.githubusercontent.com/maryannh/sts_pi_controller/master/static/images/screen1.png)

From there you just need to type commands into the window.

You'll need Flask:

```
sudo pip install Flask
```

You'll also need the Pimoroni Explorer HAT library:

```
curl get.pimoroni.com/explorerhat | bash
```

And then you should reboot.

```
sudo reboot
```

## Installing and using the controller

Just clone this repo or download the zipped version:

```
git clone https://github.com/maryannh/sts_pi_controller.git
```

Then, move into the `sts_pi_controller` directory and run the app:

```
cd sts_pi_controller
sudo python app.py
```

The app will now be running on port 80 at the IP address of your Pi. Just
enter that address in your browser and away you go!
