# 🔒 BLE Door Opener

A modern web application that allows users to unlock a Bluetooth Low Energy (BLE) door lock using the Web Bluetooth API directly from their browser.

![BLE Door Opener Screenshot](screenshot.png)

_Made with ❤️ by [Iheb Mrabet](https://github.com/Ihebmrabet0)_

## 🚀 Features

- **User Authentication:** Enter username and password to authenticate.
- **BLE Connection:** Connects to a BLE door lock named **"NimBLE Servo Lock 3"**.
- **Unlock Door:** Sends commands to unlock the door.
- **Characteristic Scanning:** Scan and display available characteristics of the BLE service.
- **Responsive Design:** Modern UI optimized for desktop and Android mobile devices.

## 📋 Prerequisites

- **BLE Door Lock Device:**
  - Must be named **"NimBLE Servo Lock 3"**.
  - Uses the specified service and characteristic UUIDs.
- **Supported Browsers:**
  - **Desktop:**
    - Google Chrome (version 56 or higher)
    - Microsoft Edge (version 79 or higher)
  - **Mobile:**
    - Chrome for Android (version 56 or higher)
- **Note:** The Web Bluetooth API is **not supported** on iOS devices (Safari or Chrome on iOS).
