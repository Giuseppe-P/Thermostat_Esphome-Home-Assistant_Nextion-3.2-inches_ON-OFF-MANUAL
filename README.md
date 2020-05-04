# Thermostat - Esphome Home Assistant - Nextion-3.2 inches 

This version allows you to manage the thermostat via Home Assistant and in the absence of the server simply ON / OFF in manual mode touch nextion.
To carry out the project with logic even in the absence of Home Assistant and therefore in offline mode, I refer you to the specific version, always in my repository. Link project later

![IMG_20200504_171325](https://user-images.githubusercontent.com/15862510/80982771-0c0b6500-8e2c-11ea-923e-0a722314a267.jpg)
![Manual ON OFF](https://user-images.githubusercontent.com/15862510/80983071-6d333880-8e2c-11ea-8b7c-6b510ea3e4b4.jpg)
![IMG_20200504_171339](https://user-images.githubusercontent.com/15862510/80982779-0dd52880-8e2c-11ea-992c-8776021a4583.jpg)
![IMG_20200504_171421](https://user-images.githubusercontent.com/15862510/80982784-0f9eec00-8e2c-11ea-9e0e-151c932e8e59.jpg)

Home Assistant - Thermostat Touch Nextion - Firmware ESPHOME

This is a generic Home Assistant thermostat, managed by an ESP8266 chip and a 3.2 "Nextion touch screen panel.

ESPHOME documentation:
https://esphome.io/index.html

Home Assistant documentation:
https://www.home-assistant.io/

NEXTION documentation:
https://nextion.tech/

Hardware needed:

1 - RaspberryPi 3 or higher

2 - ESP8266-12 chip

3 - Touch Screen Panel NEXTION 3.2 "

Software:

1 - download and copy home assistant image on sd card for raspberryPi

2 - add ESPHOME add on to your Home Assistant

3 - upload the firmware to yaml on ESP8266 via Home Assistant add on

4 - upload .HMI to next touch panel

5 - copy the configuration.yaml content and paste in configuration.yaml in Home Assistant

6 - copy the automation.yaml content and paste in automation.yaml in Home Assistant

Good realization
