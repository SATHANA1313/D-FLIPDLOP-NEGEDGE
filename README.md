# D-FLIPDLOP-NEGEDGE

**AIM:**

To implement  D flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**D Flip-Flop**

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/48c81fe8-bc3f-40e7-95e2-519fc155ad51)

This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/e5f3fda7-68ec-4a3a-a0a4-cf6f9cc4ab55)

Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/8592c0d8-2917-4142-91b9-d6c30dd891d2)

Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.



**PROGRAM**

![Screenshot 2024-12-28 212213](https://github.com/user-attachments/assets/de4b4b12-52b3-49ad-993b-fa0351b2b66a)

 
 Developed by:SATHANA.V
 
 RegisterNumber:24901144


**RTL LOGIC FOR FLIPFLOPS**


![Screenshot 2024-12-28 212223](https://github.com/user-attachments/assets/11b6f9db-4500-4189-9c28-53d0873851fd)



**TIMING DIGRAMS FOR FLIP FLOPS**


![Screenshot 2024-12-28 212235](https://github.com/user-attachments/assets/97db2bec-3bac-45d8-8cb7-37b8a2d7c96c)


**RESULTS**
Thus D flip flop is implemented and verified using verilog in quarus || and verified their functionality using functional tables.
