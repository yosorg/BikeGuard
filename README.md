# BikeGuard
BikeGuard is a system to improve bicycle ride safety. Composed of a devices and a control app, the devices will be used to signal the position and maneuvers of the bicycle and to capture and trasnmite the rear view video and the control app will be run in an Android device placed on the bike's handlebar.

## BikeView
[BikeView](https://github.com/yosorg/bike-view) is the Android app in charge of the control of the lights and the rear view video display. It also uses the device light and motion sensors to automate light and brake lights.

## BikeCam
[BikeCam](https://github.com/yosorg/bike-cam) is the device responsible for capturing video and manage the RGB ligts. It's based on the **Raspberry Pi Zero W** and comunicates via WiFi with the BikeView app. 

## BikeLed
Non-camera versions of BikeCam based on **ESP32** or **Arduino** will be developed.
