# JKFLIPFLOP-USING-IF-ELSE

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**

1.Open Quartus II and create a new project wizard.

2.Create a Verilog HDL file and enter the JK Flip-Flop code.

3.Save the file.

4.Click Compile to check for errors and build the design.

5.Go to Tools > Netlist Viewers > RTL Viewer to view and save the RTL schematic.

6.Create a Vector Waveform File (.vwf) via File > New > University Program VWF.

7.Add input/output nodes using Node finder.

8.Apply different input combinations (J, K, Clock) in the waveform.

9.Run Simulation from Processing > Start Simulation.

10.View and save the timing diagram showing the JK flip-flop behavior.

**PROGRAM**

![Screenshot 2025-05-05 141744](https://github.com/user-attachments/assets/3625e83d-e6d9-4824-b0df-258cce26be0e)


Developed by: ARUNRAJ R
RegisterNumber:212224110006

**RTL LOGIC FOR FLIPFLOPS**


![Screenshot 2025-05-05 141222](https://github.com/user-attachments/assets/57ddadad-96b6-4b8c-90ca-8c3f04ed3ac3)



**TIMING DIGRAMS FOR FLIP FLOPS**


![Screenshot 2025-05-05 141236](https://github.com/user-attachments/assets/170ca1b9-c12e-4360-812e-9afa1a53b86b)



**RESULTS**
    JK flipflop using verilog and validating their functionality using their functional tables are verified.
