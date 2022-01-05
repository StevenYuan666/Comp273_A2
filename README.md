# Sequential Circuits
## Led
### Introduction
Implemented a sequential circuit that displays my McGill ID one digit at a time on a row of 10 LED lights (shown below). The only input is the clock.

![image](https://user-images.githubusercontent.com/68981504/148277766-dd094dcf-ed8b-4d0b-b368-7aca675ba5fe.png)

### Design

![image](https://user-images.githubusercontent.com/68981504/148278326-3c00dd0b-708a-4fa3-961c-d31153bee6d0.png)

## Sequential Multiplication
### Introduction
Created a sequential circuit that implements a 4 bit unsigned multiplier following the design of the simple sequential multiplier. This circuit has a RESET input. On a rising clock edge, when RESET is high, the circuit will initialize its internal registers with the 4-bit inputs A and B, and then start the multiplication on subsequent clock cycles when RESET is low. The circuit also provides a DONE signal that goes high when the 8-bit result is ready. 

### Design
![image](https://user-images.githubusercontent.com/68981504/148278449-797c4032-8b11-4b67-8d4f-87b85673efc4.png)

## Sequential Division
### Introduction
Created a sequential circuit that implements 4-bit unsigned division. 

### Design
![image](https://user-images.githubusercontent.com/68981504/148278583-f80abdd4-3f18-4d36-91f1-0c575661221a.png)
