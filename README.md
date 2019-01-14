# AppKiosk
It consists of completely blocking the use of other smartphone applications and functions. Restricting use to this app only.

## Installing</br>
[![API](https://img.shields.io/badge/API-23%2B-brightgreen.svg?style=flat)](https://developer.android.com/about/versions/marshmallow/android-6.0)

  1- Restore the factory settings; </br>
  2- Skip the Google Add Account Step;</br>
  3- Install app:</br>
  
```
$ adb install path/to/kiosk.apk
```
  4- Set the app as device administrator:</br>
  
```
$ adb shell dpm set-device-owner com.jonasvieira.kioskmode/.MyDeviceAdminReceiver
```

## Screenshots</br>
<p align="center">
  <img src="arts/kioskDisable.png" width="250" title="hover text">
  <img src="arts/kioskEnable.png" width="250" alt="accessibility text">
  <img src="arts/kioskExit.png" width="250" alt="accessibility text">
</p>

## Author</br>
* Jonas Vieira - jonasvieira.ti@gmail.com </br>
[![LinkedIn](https://img.shields.io/badge/LinkedIn-JonasVieira-blue.svg)](https://br.linkedin.com/in/jonasvieirati)
