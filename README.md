# STM8_Adventure
STM8 adventure things

## Problem with STM8 programming
The gound pin of the STM8 blue chinese board's GND wont be connected to the system ground! Connect a wire to make it respond to STMV2 commands.
![101233105-84acfb00-3673-11eb-868e-7bc35a938150 (1)](https://user-images.githubusercontent.com/5345014/136696622-ede02f3e-d297-46bb-81d0-a6b8d5eacb5a.jpg)

issue: 
```
Determine FLASH area

Determine FLASH area

libusb: warning [windows_get_device_list] could not retrieve port number for device '\\.\USBESTUB#DEVICES#0000', skipping: [13] The data is invalid.
libusb: warning [windows_get_device_list] could not retrieve port number for device '\\.\USBESTUB#DEVICES#0001', skipping: [13] The data is invalid.
libusb: warning [windows_get_device_list] could not retrieve port number for device '\\.\USBESTUB#DEVICES#0000', skipping: [13] The data is invalid.
libusb: warning [windows_get_device_list] could not retrieve port number for device '\\.\USBESTUB#DEVICES#0001', skipping: [13] The data is invalid.
Due to its file extension (or lack thereof), "C:\Users\MANUKR~1\AppData\Local\Temp\arduino_build_34761/Blink.ino.hex" is considered as INTEL HEX format!
1821 bytes at 0x8000... Tries exceeded
An error occurred while uploading the sketch


```
Rectified output
```
Determine FLASH area

libusb: warning [windows_get_device_list] could not retrieve port number for device '\\.\USBESTUB#DEVICES#0000', skipping: [13] The data is invalid.
libusb: warning [windows_get_device_list] could not retrieve port number for device '\\.\USBESTUB#DEVICES#0001', skipping: [13] The data is invalid.
libusb: warning [windows_get_device_list] could not retrieve port number for device '\\.\USBESTUB#DEVICES#0000', skipping: [13] The data is invalid.
libusb: warning [windows_get_device_list] could not retrieve port number for device '\\.\USBESTUB#DEVICES#0001', skipping: [13] The data is invalid.
Due to its file extension (or lack thereof), "C:\Users\MANUKR~1\AppData\Local\Temp\arduino_build_34761/Blink.ino.hex" is considered as INTEL HEX format!
1821 bytes at 0x8000... OK
Bytes written: 1821

```

## Arduino Pinouts

![Arduino-Pin-Mapping-for-STM8S103F3](https://user-images.githubusercontent.com/5345014/136696721-54a1c405-c755-40ae-b2b2-260931cb37ea.png)

