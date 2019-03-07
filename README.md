# GS2200-WiFi

[GS2200 WiFi add-on board](https://idy-design.com/product/is110b.html) operation

![image](./extras/iS110B.jpg)

## Description

SPRESENSE-WiFi is the sample program to kick GS2200 for the WiFi data transfer.

## Features

- TCP Client : After connecting TCP server, it sends data on and on....

## Requirement

- Arduino IDE
- Need to install <GS2200> library, otherwise you will have the compile error
- This will help you. (http://stupiddog.jp/note/archives/266)

## Usage

Change MACRO in AppFunc.cpp.
- AP_SSID : SSID of WiFi Access Point to connect
- PASSPHRASE : Passphrase of AP WPA2 security
- TCPSRVR_IP : TCP Server IP Address
- TCPSRVR_PORT : TCP Server port number

## Document
- Visit GS2200 AT Command Document (https://y1cj3stn5fbwhv73k0ipk1eg-wpengine.netdna-ssl.com/wp-content/uploads/2018/02/GS2200M-S2W-Adapter-Command-Reference-Guide_r3.0.pdf)

## Author

Norikazu Goto

## License

[LGPL](http://www.gnu.org/licenses/lgpl.html)

