![](https://github.com/nmilford/stormLauncher/raw/master/stormLauncher.png)

# Storm Launcher

Controls the Dream Cheeky [O.I.C Storm](http://www.dreamcheeky.com/storm-oic-missile-launcher) & [Thunder](http://www.dreamcheeky.com/thunder-missile-launcher) USB Missile Launchers.  

There are a few projects for using older launchers in Linux, but I couldn't find any for this launcher, so... enjoy.

This script requires PyUSB 1.0+, apt in Debian/Ubuntu installs 0.4.

Also, on Debian\Ubuntu systems you need the __python-imaging-tk__



## Getting Started:

    git clone git@github.com:nmilford/stormLauncher.git
    cd stormLauncher
    sudo cp 54-missilelauncher.rules /etc/udev/rules.d
    sudo service udev restart
    ./stormLauncher.py

## Usage:

* Use arrow keys aim.
* Press return to fire.
