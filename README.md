# CSN150-first
first github repo
# Wifi example
| Supported Targets | ESP32 | ESP32-S2 | ESP32-C3 | ESP32-S3 | ESP32-C6 |
| ----------------- | ----- | -------- | -------- | -------- | -------- |
* Before Compile/Verify, select the correct board: `Tools -> Board`.
* Select the COM port: `Tools -> Port: xxx` where the `xxx` is the detected COM port.

#### Using Platform IO

* Select the COM port: `Devices` or setting the `upload_port` option on the `platformio.ini` file.

Begin with identifying personal wifi and password to connecected wifi. 
problems occured when nothing appeared in serial port
solution; Disconnected usb, re-entered wifi and password
finially scanning for wifi was possible
  
## Example/Log Output

```
Setup done
Scan start
Scan done
17 networks found
Nr | SSID            | RSSI | CH | Encryption
 1 | IoTNetwork      |  -62 |  1 | WPA2
 2 | WiFiSSID        |  -62 |  1 | WPA2-EAP
 3 | B3A7992         |  -63 |  6 | WPA+WPA2
 4 | WiFi            |  -63 |  6 | WPA3
 5 | IoTNetwork2     |  -64 | 11 | WPA2+WPA3
