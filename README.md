# Tindev Mobile

Moile app built with React Native and works with the server built with Node.js and web version built with React from this project.

## **Links**
[Server](https://github.com/enzorossetto/tindev-server)

[Web version](https://github.com/enzorossetto/tindev-web)

***

## **Instructions**

In the project directory, you can run:

_**`react-native start`**_ to start the application run on your terminal

Then with your phone connected via USB run on a new terminal tab
- _**`react-native run-android`**_ if on Android 
-  _**`react-native run-ios`**_ if on iOS

**Note:** If using Android run on terminal the command _**`adb reverse tcp:3333 tcp:3333`**_ with your phone connected via USB and with USB debugging on. Or change **`baseURL`** on **api.js** to "http://yourIP:3333".
