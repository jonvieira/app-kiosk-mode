# AppKiosk
App Kiosk, que bloqueia completamente o uso de outros aplicativos e funções do Android. Restringindo o uso apenas à este aplicativo

## Procedimento</br>
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
