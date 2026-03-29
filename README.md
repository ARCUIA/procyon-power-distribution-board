# procyon-power-distribution-board
Power distribution board responsible for managing power for the Atlas flight controller, up to 3 FPV camera + VTX systems, a radio module, and a DC motor. Toggle-able camera power to save battery. Support for High-side switching, allowing for chassis grounding on VTX modules.

### V1 Typical Application
- Battery: 2S LiPo 5000 mAh
- Flight Controller: Atlas V3
     - Input Voltage: 5V
     - Inpue Current (max): 250 mAh
- Motor: BLDC RS-380SH-4535
     - Input Voltage: 5V
     - Input Current: <1 amp
- Radio: RFD900X
     - Input Voltage: 5V
     - Input Current: 1 amp
- FPV Systems: CADDX Walksnail Avatar HD Pro
     - Input Voltage: Battery (Minimum 6V)
     - Input Current: 0.5-1 amp
