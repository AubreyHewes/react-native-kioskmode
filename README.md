# react-native-kioskmode

Tries to give a kiosk 

### enable

````javascript
KioskMode.enable().then(status => console.log(status));
````

### disable

````javascript
KioskMode.disable().then(status => console.log(status));
````

## Android Only
 
    startLockTask()
 
Tries device owner, without a device owner anyone can exit the kiosk.

Also / etc 

 * Keeps screen from dimming
 * Keeps screen from locking
 * Blocks power button; kiosk is enabled then resets the request
 * Blocks power button long press dialog; kiosk is enabled then resets the request
 * Can never block a proper power reset

# WIP Moving from BitBucket
