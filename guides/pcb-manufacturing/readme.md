# Farmduino Manufacturing Notes
The gerber files do not contain designators for all through-hole components. That's why manufacturers will have a hard time to locate the correct location on the board for these components. This guide illustrates the right spots on the board for all through-holes.

![Overview](/guides/pcb-manufacturing/overview.png "Overview")

### Encoder Headers
The encoder header designators P8, P9, P10, P11 match to the logical encoders Z, Y, X2, X1
* p8 -> Z ENCODER
* P9 -> Y ENCODER
* P10 -> X2 ENCODER
* P11 -> X1 ENCODER

![Encoders](/guides/pcb-manufacturing/p8-p9-p10-p11.png "Encoders")
### 12-pin header P17
The P17 header is located at the lower left corner of the board.
![12-pin header](/guides/pcb-manufacturing/p17.png "12-pin header")
### 4-pin motor headers X3..X7
The 4-pin headers X3, X4, X5, X6, X7 for connecting the stepper motors are located at the upper side of the board and match to the logical motor identifiers.
* X3 -> X2 MOTOR
* X4 -> AUX MOTOR
* X5 -> X1 MOTOR
* X6 -> Y MOTOR
* X7 -> Z MOTOR

![motors](/guides/pcb-manufacturing/x3-x4-x5-x6-x7.png "motors")
### 5-Pin UTM header
The 5-pin header with designator P2 is located at the lower bottom of the board.
![utm](/guides/pcb-manufacturing/p2.png "utm")
### 12-Pin header P20
The 12-pin header with designator P20 is located at the lower bottom of the board.
![utm](/guides/pcb-manufacturing/p20.png "utm")
### Fuse and fuse holder
The original Farmduino BOM lists *0287015.H* from *Littlefuse* as primary component for designator F1, but the two fuse blades do not fit to the four through-holes. The missing piece is a fuse holder that is soldered first. The fuse is put manually into the slot of the fuse holder, e.g. *3557-2* from *Keystone*.
1. Fuse F1
![fuse](/guides/pcb-manufacturing//f1.png "fuse")
2. Fuse holder
![fuse holder](/guides/pcb-manufacturing/f1-2.png "fuse holder")