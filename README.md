# Stardew Valley Wear OS Watchface 
## Description
Stardew Valley themed watch face for Wear OS smartwatches created in Google's WFF using Samsung's Watch Face Studio.

## Features
![Stardew Valley DEMO GIF](https://github.com/user-attachments/assets/c67a0536-6ab4-4376-859a-cc5625465f78)

The watchface displays the following information: 
- **Time**: Separate 12/24 hour versions available for download.
- **Date**: The date/time area acts as a shortcut to open the calendar application on the watch.
- **Battery**: The energy bar shows the battery status of the smartwatch. The colour of the bar changes as you lose energy/battery. The exhaustion icon is displayed when the battery is below 15%. The battery bar acts as a shortcut to open the watch's battery settings (_only on the Samsung versions_).
- **Day progress**: The arrow moves according to the time of day.
- **Steps**: The current number of steps (S) is displayed instead of a gold counter. The steps area acts as a shortcut to open the Samsung Health app on the watch (_only on Samsung versions_).
- **Temperature**: In addition to the step counter, there is a second counter showing the current temperature (T) (_V34 versions only_). The temperature section acts as a shortcut to open the Samsung Weather application on the watch (_only on the Samsung versions_).
- **Notifications counter**: If you have an unread notification, the journal icon will be displayed.
- **Seasons icon**: The season icon doesn't change according to the current season. You can change the icon manually by customising the watch face.
- **Weather icon**: The weather icon changes according to the current weather (_only on V34 versions; on V30 versions, the festival icon is always displayed_). **Credit:** Special thanks to Kanadeyoru for allowing me to use the assets from the _Weather Wonders_ mod.
- **Background**: Different backgrounds for day and night (based on sunset and sunrise times). (_V34 versions only_)

## Versions
Each version has a separate 12/24 hour format version.
### V34 Samsung Version
- Designed for Samsung smartwatches with SDK/API level 34+ only 
- Additional features:
  - Weather features: Temperature and weather icons 
- App shortcuts: Shortcuts to Samsung Health and Weather app.
### V34 Version 
- Designed for all WearOS smartwatches with an SDK/API level of 34+ 
- Additional features:
  - Weather features: Temperature and Weather icons 
### V30 version 
- Designed for all WearOS smartwatches with an SDK/API level of 30+ 

## Installation Guide
### What you need
- **Watch Face Studio**: Download and install Samsung Watch Face Studio on your PC (https://developer.samsung.com/watch-face-studio/download.html).
- **Watchface**: Download the correct version of the Watchface.

### How to pair your watch and send the watchface to your watch
- See more detailed Guide here: https://www.reddit.com/r/GalaxyWatch/comments/15jo3u4/tutorial_how_to_pair_your_galaxy_watch_with_watch/
- Enable Developer settings on your watch (Settings/About Watch/Software/ tap 7+ times Softwareversion)
- Enable WiFi and connect to the same WiFi as your PC (keep in mind, if you're connected to your phone it doesn't (always) stay connected to the WiFi)
- Go into Developer Developer and turn on "ADB debugging"
- Scroll further down, go to "Wireless Debugging" and turn it on. Even if your WiFi is turned on and connected, you may get errors. Simply tap/enable again until it's activated
- In Wireless Debugging, when it's finally activated you'll see the IP address and IP port of your watch. There you tap on "Pair device". It'll show you a new windows with your Wifi "Pairing Code" and below it shows you an IP address and IP port. The IP address is the same as your from your watch, but the IP Port is your "Pairing Port".
- On your PC in WFS press "Run on Device"
- Press the Plus button (+) at the top right to add a device (your watch)
- You have to enter 4 values: IP, IP port, Pairing code and Pairing port.
- The window "Connected Devices" should now show your watch. If not, you need to press "Scan devices" and it should be listed there!
- Select your device, let it transfer and it should be on your watch now! Enjoy!
