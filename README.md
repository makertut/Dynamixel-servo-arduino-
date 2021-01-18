# Dynamixel-servo-arduino-

Hardware
1. Arduino Uno
2. IC 74LS241
3. Breadboard
4. Resistor 10K ohm
5. Dynmixel AX-12A

Dynamixel Servo Ax12A Library

https://github.com/jumejume1/AX-12A-servo-library

IC 74LS241 Pin out
![Maker Tutor](https://2.bp.blogspot.com/-nuNAjKlgayQ/Wm7tyYVYPdI/AAAAAAABANE/v7TxKCNlVEY0X7RibNVjAiODyK7_aQHuQCLcBGAs/w400-h354/74LS241-634933661703906250.jpg)
![Maker Tutor](https://3.bp.blogspot.com/-uiekcEzafyU/Wm7trpZiIGI/AAAAAAABANA/oGn-dDzoHPQGIk6Y0imhS-F4UGoh3Bm8gCLcBGAs/s640/g4084.png)
Schematic diagram
![](https://3.bp.blogspot.com/-5z_xCRi2_IA/Wm6RQb6rbdI/AAAAAAABAIc/BBZIP_DgDAcuWtfGwlymuSlqUDPHnQ4uQCLcBGAs/s640/ax120half_bb.jpg)

//  function AX12A.h
int readTemperature(unsigned char ID);
int readVoltage(unsigned char ID);
int readPosition(unsigned char ID);
int readSpeed(unsigned char ID);
int readLoad(unsigned char ID);
