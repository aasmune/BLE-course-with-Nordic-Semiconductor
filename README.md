# BLE-course-with-Nordic-Semiconductor
Custom BLE service made during Bluetooth course with Nordic Semiconductor and Omega Verksted

## Requirements
* Nordic SDK 14.1.0
* Segger Embedded studio 3.30
* nRF52832 devkit

## Getting Started
1. Download the SDK and unzip it in your home folder.
2. Clone the repo to the following path `~/NordicSemi/SDK_14_1/examples/ble_peripheral/` where the zip were extracted to `~/NordicSemi/SDK_14_1/`
3. Open the ses project found in `p10040/s132/ses/`under the root path in this repo.


**NOTE:**
You may need to change the path to the Softdevice hex file in the project options from relative to absolute. 
This can be done by right clicking the project and selecting `Edit Options -> Debug -> Loader` and changing  `Additional Load File[0]` to the absolute path of the softdevice hex that is located in `~/NordicSemi/SDK_14_1/components/softdevice/s132/hex/s132_nrf52_5.0.0_softdevice.hex`.
