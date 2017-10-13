
## Installing NodeJS on your Raspberry Pi

### Downloading Binaries from https://nodejs.org/en/download/  

1. Download the Linux ARM Binaries (The current LTS version of NodeJS is 6.11)

&nbsp;&nbsp; ARMv6 will cover Raspberry Pi models A, A+, B, B+ and the Pi Zero 
&nbsp;&nbsp; You can download the binaries from the site OR using the following command 
&nbsp;&nbsp;> wget https://nodejs.org/dist/v6.11.4/node-v6.11.4-linux-armv6l.tar.xz 

2. Extract the Binaries 
> tar -xvf node-v6.11.4-linux-armv6l.tar.xz 
&nbsp;&nbsp; This will create a directory with the same name i.e. node-v6.11.4-linux-armv6l
3. Copy binaries to /usr/local/ 
> cd node-v6.11.4-linux-armv6l
> sudo cp -R * /usr/local/ 

REFERENCES 
https://webofthings.org/2016/10/23/node-gpio-and-the-raspberry-pi/ 
https://blog.wia.io/installing-node-js-on-a-raspberry-pi-3 

### Using node source distribution  

> curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash - 

> sudo apt-get install -y nodejs 

> sudo apt-get install -y build-essential 


REFERENCES 

https://raspberrypi.stackexchange.com/questions/45319/install-newer-node-version-on-pi-3 

https://github.com/nodesource/distributions#installation-instructions 

http://thisdavej.com/beginners-guide-to-installing-node-js-on-a-raspberry-pi/#install-node 
