# Drink-Minder
Drink Minder Smart drink coaster for VRC and OBS.

Ever wanted to show the level of your Real life drink in realtime while in VRC or as a overlay in OBS? Now you can.

If you received a unit directly from me, proceed to the Drink Minder setup.pdf instuctions located in this Repository.

Please note that OBS fucntions are beta a the moment and do not have setup instructions yet.


Flashing new firmware (if needed or instructed to)

1. Get and Run "ESPHome-Flasher" from https://github.com/esphome/esphome-flasher/releases/download/1.4.0/ESPHome-Flasher-1.4.0-Windows-x86.exe

2. Check and take note of the list of availible Serial COM ports (you may have multible)

3. Connect usb from the drink minder to your computer

4. Click the reload button in the flasher, then look for the newly added port

5. Select the correct the new Com port *remember it's number!

6. Click browse and select "Drink Minder esp8266 (version #).ino" in the Drink Minder folder

7. Click Flash ESP

8. Wait for the flash to complete, The console log will just continually loop and show "Welcome to first time setup! Press enter to continue"

9. Close the flasher

10. Refer to setup instructions if needed



