#PKU_CGM

`PKU_CGM` is a companion app for the artificial pancreatic system, and compiile code using Uniapp.

- [Overview](#overview)
- [System Requirements](#system-requirements)
- [Installation Guide](#installation-guide)
- [License](#license)

# Overview

`PKU_CGM` can search for and connect Bluetooth, monitor the sensor current, control the voltage of the sensor and the insulin pump, and run a hybrid closed-loop control algorithm to show the historical trend of blood glucose changes.

# System Requirements
## Hardware requirements
`PKU_CGM` package requires a standard mobile phone with enough RAM and bluetooth to support the operations.

## Software requirements
### OS Requirements
This package is supported for *Android*. The package has been tested on the following systems:
+ Andorid 13

## non standard hardware



# Installation Guide:

## Install from Github
```
https://github.com/pkuzhangcx/PKU_CGM
```

## Complie from Github

### Download Hbuilder X
```
https://www.dcloud.io/hbuilderx.html
```
### import code form Github
```
https://github.com/pkuzhangcx/PKU_CGM
```

### complie the code
click the file and import the code from the local



# User Guide:
### Connect bluetooth device
click the button 'Start Bluetooth Devices Discovery' to discorvery the bluetooth devices
choose the bluetooth device named 'minigril' and click it.
click the device number to connected, and then you can get the divice ID, Service Id, Write Id and Notify Id.

### set up settings
You can click the button 'go System settings' to set the calibreation curve coeffcient, the amount of insulin injection before meals, the maximum 2 hour inluslin pump dose, the maximum 2hour insulin pump dose at night, and the daytime begin and end.

You can click the button 'go Strategy settings' to set the blood glucose limit and pump output voltage to change different mode of algorithm.
### open algorithm
Click the button 'go BTlog' to jump to work page.
Click the button 'notify' to notify the current change from bluetooth devices before run the algorithm.
Click the button 'open the strategy' to run the algorithom, and you can click the button 'close the strategy' to close the algorithm.

### before meal 
you should click the button 'open before meal(auto)' before eating, 

### expect output
You can find the current notified from the bluetooth devices every five minutes from the vertical column of the 'current log'.
You can find all opretion records of the app from the vertical column of the 'opretion log'.
You can find the current value of the last 10 seconds to determine if the device is functioning properly from the vertical column of the 'recent current'.

### expect output chart
You can click the button 'go figure' to get the linechart and piechart which are used to provide a better assessment of your blood glucose level.

### expect run time
The APP can remain running continuously.
Please keep the screen on and not switch to the background while using the app.

# License

This project is covered under the **MIT License**.
