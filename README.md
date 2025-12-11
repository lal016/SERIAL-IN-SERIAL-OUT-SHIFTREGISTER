# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

1).Compile and run the program.

2).Generate the RTL schematic and save the logic diagram.

3).Create nodes for inputs and outputs to generate the timing diagram.

4).For different input combinations generate the timing diagram.

**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming.

<img width="1093" height="465" alt="image" src="https://github.com/user-attachments/assets/fa019b3c-6fcf-4ef7-9295-039edc661adb" />


Developed by:LAL RHIDHISHAN.R, RegisterNumber:25015767

*/

**RTL LOGIC FOR SISO Shift Register**

<img width="1280" height="703" alt="image" src="https://github.com/user-attachments/assets/e3db3253-a67f-4e6f-ac02-b91bcb6b623d" />


**TIMING DIGRAMS FOR SISO Shift Register**

<img width="1234" height="665" alt="image" src="https://github.com/user-attachments/assets/eb5da2ff-f15a-4e6e-87ce-f7b1c215a9f7" />

**RESULTS**

SISO Shift Register using verilog and validating their functionality using their functional tables has successful execution of the program.
