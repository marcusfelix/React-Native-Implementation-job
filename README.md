# React Native implementation task
tags: android, react-native, bluetooth

Device info: http://www.pax.us/portfolio_page/d200/
GitHub repo with library and example: https://github.com/pagseguromaster/plugpag
Docs: https://dev.pagseguro.uol.com.br/documentacao/pagamento-presencial/moderninha-wifi/android (PT-BR)

The main goal of this task is to expose some methods from another github repo and wrap on NativeModule package. Our objective is connect and operate an BLE (Bluetooth Low Energy aka.: Bluetooth 4.0) device through a NativeModule exposed methods. Fist, we need to seek and connect to device, and then, be able to send payments commands to it. All methods are listed on official  docs. There is an example named "pagcafe" within the repo.

Obs.: We are going to use this package on Android Things device (Raspberry Pi3). Android Things use the same methods from Android OS to seek and connect to BLE devices.
