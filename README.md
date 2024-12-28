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

1.Start a New Project in Quartus:

  • Open Quartus Prime and create a new project.
  • Define the project name and directory location.

2. Write the Verilog Code for JK Flip-Flop:

  • Use the if-else statement to describe the behavior of the JK flip-flop.

3. Compile and Simulate:

  • Compile the design in Quartus.
  • Simulate the design using the simulation tool to verify the functionality against the truth table.

4. Analyze the Results:

  • Check the output waveform to verify the correct operation of the JK flip-flop based on different input combinations.


**PROGRAM**

![jk_flipflop_code](https://github.com/user-attachments/assets/98d7863d-7f99-4f74-96e4-6d719ece8016)




**RTL LOGIC FOR FLIPFLOPS**

![jk_flipflop_rtl](https://github.com/user-attachments/assets/6daf2a6e-5e4e-4cf5-8fde-64ef3c80697f)


**TIMING DIGRAMS FOR FLIP FLOPS**

![jk_flipflop_waveform](https://github.com/user-attachments/assets/163ba71e-1854-4399-9497-5a3d95584524)


**RESULTS**

• The Verilog code for the JK flip-flop works correctly as per the truth table.

• The simulation results match the expected behavior of the JK flip-flop.

• The timing diagram in Quartus will show the accurate transitions of the Q output based on the input conditions.

• The functionality of the JK flip-flop (Hold, Reset, Set, Toggle) is validated using the simulation.



