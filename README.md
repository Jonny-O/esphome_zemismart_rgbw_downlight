# ESPHome Zemismart RGBW Downlight
Control Zemismart RGBW Downlights through Home Assistant or via DDP

This is an ESPHome YAML config that I generated to control a Zemismart 10W RGBW 6-inch downlight.  It allows the light to be fully controlled through Home Assistant and also communicates via the DDP protocol used by many lighting control programs, including xLights and WLED.

**Please note that this is ONLY for earlier-generation Zemismart downlights.** (For reference: mine were purchased in the Q1/2019 timeframe.)  Zemismart has since modified the light design; unfortunately this code will not work with the lights currently on sale.

Rob from The Hook Up made a detailed video that shows how to crack open the light fixture and reprogram it: https://www.youtube.com/watch?v=r5gju3l6AFQ

PSA for those who don't want to use ESPHome: 
- Rob also wrote some Arduino sketches that can also control the lights. Multiple flavors are available, depending on the type of control you are looking for.
- Tasmota is supposed to work on these lights, but the light control is problematic. At the time of this writing, DDP support is limited to ESP32-powered devices, though it appears that ESP8266 support is coming.
- WLED and ESPixelStick are not compatible, as they will not fit.

Standard disclaimer for this type of activity applies: there is a risk of damaging your device and/or yourself when modifying code and playing with electricity. Proceed at your own risk and don't take on a task you're not comfortable doing!
