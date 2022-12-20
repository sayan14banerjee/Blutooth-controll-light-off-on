# Blutooth-controll-light-off-on
Phone control light is very common nowadays. you can buy this from the market. but today we are making the same on very low cost. this phone control light can be use anywhere you have just plug it and operate with your mobile phone. there is an app which will control the light.
light.

#devises
•	Arduino Uno
•	Bluetooth HC-05
•	5v 4th-channel Relay
•	Led Bulb
•	Some wires

# First Install Arduino IDE
Download Link - https://www.arduino.cc/en/software


 Get the latest version from the download page. You can choose between the Installer (.exe) and the Zip packages. We suggest you use the first one that installs directly everything you need to use the Arduino Software (IDE), including the drivers. With the Zip package you need to install the drivers manually. The Zip file is also useful if you want to create a portable installation.

When the download finishes, proceed with the installation and please allow the driver installation process when you get a warning from the operating system.

Choose the components to install.


Choose the installation directory.


Installation in progress.


The process will extract and install all the required files to execute properly the Arduino Software (IDE)

The text of the Arduino getting started guide is licensed under a Creative Commons Attribution-ShareAlike 3.0 License. Code samples in the guide are released into the public domain.
 
# Run the code and upload it to arduino
 first run the code in ide. Before upload it please check the port. Neither it will give some error. Dont exact copy the code, it occurs somr error because during copy some letter may add with the code.
 
# set the circuit as show as diagram
 connect the ports as following
blutooth hc-05  TO  arduino

VCC                 VIN

GND                 GND

TX                  RX

RX                  TX

relay    to      arduino

1,2,3....        A1,A2,A3.....

GND              GND

VCC              5V
