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
|V1.0.2|1. OUT_1 port outputs a stall indicator.<br/>2. When using a broadcast CAN ID or a packet CAN ID, the
slave device does not respond.|V1.0.2|May-2023|
|V1.0.3|1. Added serial command to set single-turn zero return parameter (9 AH ).<br/>2. Added a serial command lock button ( 8FH).<br/>3. Add IO port status reading function (34H).<br/>4. The menu allows setting up to 16 slave CAN IDes.<br/>5. Add left and right limit functions.|V1.0.3|Jul-2023|
|V1.0.4|1. Added a menu or command ( 9BH) function to set the percentage of shutdown holding current.<br/>2. Add absolute motion based on pulse count ( FEH ).<br/>3. Modify the 8C instruction to add the option of not actively initiating data.<br/>4. Add emergency stop command ( F7H ).<br/>5. Add limit port remapping instruction ( 9EH ).|V1.0.3|Jul-2023|


