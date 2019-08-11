# Tindev Mobile

Moile app built with React Native and works with the server built with Node.js and web version built with React from this project.

## **Links**
[Web version](https://github.com/enzorossetto/tindev-web)

***

## **Instructions**

To start the aplication run on your terminal _**react-native start**_

Then with your phone connected via USB run on a new terminal tab
- if on Android  _**react-native run-android**_
- if on iOS  _**react-native run-ios**_

**Note:** If using Android run on terminal the command _**adb reverse tcp:3333 tcp:3333**_ with your phone connected via USB and with USB debugging on. Or change **baseURL** on **api.js** to "http://yourIP:3333".
