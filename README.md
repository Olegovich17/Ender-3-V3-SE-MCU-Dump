# Ender-3-V3-SE-MCU-Dump
FW: 1.0

## Dump of the CR4NS200320C13 motherboard microcontroller for recovery when replacing the GD32F microcontroller.
### At your own risk!
1) You need a ST-Link USB adapter
2) ST-Link Utility

##  If the controller does not allow you to connect on (ST-Link Utility) to it you need to apply +3.3 before R41 to switch to boot mode.
  
  1) !To flash the firmware via ST-LINK, you do not need to apply the main voltage (+24). All voltages must be taken from the ST-Link adapter!
  2) !Do not update the firmware with SWD disabled; you will not be able to connect again via ST-LINK without boot mode (+3.3 befor R41)!
  3) !Be sure to do a full dump(with correct size from 0x08000000 to real end address of memory) before any manipulations with the MB!

<img width="1080" height="1080" alt="map" src="https://github.com/user-attachments/assets/30116f18-0651-4a6f-8269-53f6ceab72ee" />
<img width="694" height="889" alt="st-link utility" src="https://github.com/user-attachments/assets/4d03edfb-1d0d-4d81-90ba-76959bccad64" />
