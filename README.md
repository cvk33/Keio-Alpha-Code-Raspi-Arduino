# Keio-Alpha-Code-Raspi-Arduino

This code is the updated version from the first Keio Alpha Code.
Keio Alpha is a prototype hyperloop pod for Space X competition.

The pod consists of communication system (COMM), sensing system (SENS) and actuation system (ACT).
COMM: Receive Command from Ground Station (GS), Distribute Command to ACT and Receive data from SENS and send back to GS.
SENS: Receive data from individual sensors and process it and feedback to COMM.
ACT: Receive Command via i2c from COMM and perform actuation via PWM, On/Off.

COMM is achieved by Raspberry Pi (Raspi) and PHP code.
GS send command via Wifi to Raspi using PHP.
This repo contains the PHP code for COMM in Raspi with source code.

