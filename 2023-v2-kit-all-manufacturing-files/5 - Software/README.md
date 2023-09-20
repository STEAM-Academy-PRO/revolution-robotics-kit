# How to prepare the MCU
 - Install J-Link drivers
 - Connect J-Link probe to your PC
 - Connect J-Link probe to the SWD connector
    Test points:
     - TP17: 3V3, V_TARGET
     - TP20: SWCLK
     - TP23: GND
     - TP26: SWDIO
     - TP29: nRST
 - Switch on the robot
 - Run the `bootloader/flashbl2.bat` or `bootloader/flashbl2_debug.bat`. Choose the appropriate one for your use case.

# How to prepare the SD card
 - Download and install Balena Etcher from https://www.balena.io/etcher/ 
 - Download the latest release from https://github.com/RevolutionRobotics/BakeRPi/releases
 - Flash the release zip to you SD card using Etcher
