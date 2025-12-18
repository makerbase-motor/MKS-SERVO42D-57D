# MKS-SERVO42D/57D
The MKS SERVO42D/57D_RS485 closed-loop stepper motor is a product
independently developed by the Maker Base to meet market demands. It features a
pulse interface and an RS485 interface, a built-in high-efficiency FOC vector
algorithm , and a high-precision encoder . Through position feedback , it effectively
prevents step loss. It is suitable for applications such as small robotic arms , 3D
printers , engraving machines, writing machines , automation products , and e-sports
competitions .

# MKS SERVO42D/57D_CAN Version Notes
|Manual| Content | Firmware | Date | 
|------------|--------------------|--------------------|--------------------|
|V1.0.0|First release version|V1.0.0|Mar-2023|

|V1.0.1|1. Two control modes have been added: serial open-loop and serial closed-loop.<br/>2. The operating current can be set to any value.<br/>3. Speed and acceleration have been redefined, and the curve acceleration and deceleration functions have been improved.<br/>4. Added a command to set the current position to 0 O'clock.<br/>5. Added group CAN ID management.|V1.0.1|Apr-2023|

|V1.0.2|1. OUT_1 port outputs a stall indicator.<br/>2. When using a broadcast CAN ID or a packet CAN ID, the slave device does not respond.|V1.0.2|May-2023|

|V1.0.3|1. Added serial command to set single-turn zero return parameter (9 AH ).<br/>2. Added a serial command lock button ( 8FH).<br/>3. Add IO port status reading function (34H).<br/>4. The menu allows setting up to 16 slave CAN IDes.<br/>5. Add left and right limit functions.|V1.0.3|Jul-2023|

|V1.0.4|1. Added a menu or command ( 9BH) function to set the percentage of shutdown holding current.<br/>2. Add absolute motion based on pulse count ( FEH ).<br/>3. Modify the 8C instruction to add the option of not actively initiating data.<br/>4. Add emergency stop command ( F7H ).<br/>5. Add limit port remapping instruction ( 9EH ).|V1.0.4|Sep-2023|

|V1.0.5|1. Supports zero-return function for infinite position switch.<br/>2. Added " Hm_Mode " and " Hm_Ma " to the menu.<br/>3. Add (9 4H ) instruction.<br/>4. The F4 and F5 commands have been optimized to eliminate step count errors.<br/>5. The F5 command supports real-time updates of position and speed.<br/>6. Add a reset and restart motor command (41H).|V1.0.5|May-2024|

|V1.0.6|1. Added a command to read the encoder's raw value(35H).<br/>2. Added En signal-triggered single-turn zeroing and position over-tolerance protection functions (9DH).<br/>3. Added the function to read system parameters, see 5.1.10.<br/>4. Adding the En signal can disable the stall protection function.<br/>5. Add a write I/O port instruction (36H).|V1.0.6|Sep-2024|

|V1.0.7|1. The 3BH instruction adds the ability to read the zero-state value.<br/>2. The 83H instruction adds the function of changing the current value during operation without saving it.<br/>3. The F6H command adds the function of setting the runtime.|V1.0.6|Mar-2025|

|V1.0.8|1. After restoring the default parameters, there is no need to recalibrate.<br/>2. Added the function to read system parameters, see 5.1.10.<br/>3. Added multi-motor synchronous control operation function, see Part 12.<br/>4. Added a location arrival threshold setting function, see5.2.16.<br/>5. Added the function to set PID parameters, see 5.3.|V1.0.8|Jul-2025|

|V1.0.9|1. The instruction manual has been redesigned, categorized by function, and examples have been added.<br/>2. Added the function of automatically returning read-only parameters at regular intervals, see 5.1.9.<br/>3. Increase the heart rate protection time, see 5.2.15.<br/>4. Added coordinate zeroing function, see 7.2，7.7.<br/>5. Added a no-verification mode for easier testing. See 5.2.17.|V1.0.9|Nov-2025|
