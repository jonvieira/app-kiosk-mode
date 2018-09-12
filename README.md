# AppKiosk
App Kiosk, que bloqueia completamente o uso de outros aplicativos e funções do Android. Restringindo o uso apenas à este aplicativo

## Installing</br>
[![API](https://img.shields.io/badge/API-23%2B-brightgreen.svg?style=flat)](https://developer.android.com/about/versions/marshmallow/android-6.0)

  1- Fazer reset de fábrica no celular; </br>
  2- Pular a etapa de adicionar conta Google;</br>
  3- Instalar o app:</br>
  
```
$ adb install path/to/kiosk.apk
```
  4- Setar o app como administrador do dispositivo:</br>
  
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
[![Twitter URL](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet)
