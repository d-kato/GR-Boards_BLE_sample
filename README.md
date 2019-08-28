# GR-Boards_BLE_sample
It is equivalent to the following sample. Please refer to the following description.  
[BLE_LED](https://github.com/ARMmbed/mbed-os-example-ble/blob/master/BLE_LED)

The following samples that operate in the peripheral role also work. Replace the source folder and build.  
- [BLE_Button](https://github.com/ARMmbed/mbed-os-example-ble/blob/master/BLE_Button)  
- [BLE_BatteryLevel](https://github.com/ARMmbed/mbed-os-example-ble/blob/master/BLE_BatteryLevel)  
- [BLE_HeartRate](https://github.com/ARMmbed/mbed-os-example-ble/blob/master/BLE_HeartRate)  
- [BLE_Thermometer](https://github.com/ARMmbed/mbed-os-example-ble/blob/master/BLE_Thermometer)  


## Requirements
The following targets have been tested and work with these examples:

- [GR-LYCHEE](https://os.mbed.com/platforms/Renesas-GR-LYCHEE/) (RZ/A1LU)  
  - It is equipped with ESP32.  
    Please update ESP32 FW ``AT version:2.0.0.0`` or later.  


- [GR-PEACH](https://os.mbed.com/platforms/Renesas-GR-PEACH/)  (RZ/A1H)
  - [GR-PEACH Wireless CAMERA Shield](https://www.core.co.jp/product/m2m/gr-peach/audio-camera.html)  
    Please update ESP32 FW ``AT version:2.0.0.0`` or later.  


The sample application can be seen on any BLE scanner on a smartphone. If you don't have a scanner on your phone, please install:

- [nRF Master Control Panel](https://play.google.com/store/apps/details?id=no.nordicsemi.android.mcp) for Android.

- [LightBlue](https://itunes.apple.com/gb/app/lightblue-bluetooth-low-energy/id557428110?mt=8) for iPhone.


## How to update ESP32 firmware
Please refer to the following.  
https://github.com/d-kato/esp32-at-ble-stack


## Known issues
It works properly only in the peripheral role. The center role does not work properly with the ESP32 FW problem.  
