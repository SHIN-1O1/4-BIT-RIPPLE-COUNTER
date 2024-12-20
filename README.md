# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

 1.Increment count on each positive edge of the clock. 
 2.Reset count to zero when it reaches 15. 
 3.Generate clock signal (clk). 
 4.Instantiate the RippleCounter module. 
 5.Conduct functional testing by displaying the count at each clock cycle for 16 cycles.
 
**PROGRAM**
 ## Developed by: A.SHERWIN INFANO
 RegisterNumber: 24010314
![Screenshot (60)](https://github.com/user-attachments/assets/122793e8-64c1-4b15-8748-3e961c6ee0e9)


**RTL LOGIC FOR 4 Bit Ripple Counter**
![image](https://github.com/user-attachments/assets/339e9050-e4b9-4bfc-9bb2-d3d8b8261c20)

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
![image](https://github.com/user-attachments/assets/a7f9c5ef-0b3e-4195-9a33-ee8fa408c66d)

**RESULTS**
Thus the program executed succesfully.
