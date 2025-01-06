### NAME: JEEVAN VISHAL GD
### REG NO: 24900595
### EXP NO 6: IMPLEMENTATION OF SERIAL IN SERIAL OUT SHIFT REGISTER USING VERILOG HDL

### AIM:

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

### SOFTWARE REQUIRED:

Quartus prime

### THEORY:

### SISO SHIFT REGISTER:

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

### PROCEDURE:
1.Initialize the shift register to a known state (e.g., all zeros).

2.Input a bit serially into the shift register.

3.Shift the contents of the register one position to the right (or left). 

4.Output the shifted bit from the last stage of the register. 

5.Repeat steps 2-4 for each bit you want to input and shift

### PROGRAM:
![Screenshot 2024-12-31 202438](https://github.com/user-attachments/assets/e2bf625c-b9d6-4832-98bc-943858d99e53)


### RTL LOGIC FOR SISO Shift Register:
![Screenshot 2024-12-31 202425](https://github.com/user-attachments/assets/4309cda2-ed47-48b0-b41c-6974516b074c)


### **TIMING DIGRAMS FOR SISO Shift Register:**
![siso waveform](https://github.com/user-attachments/assets/6cf3657d-59a1-468a-93fc-821999861153)

### **RESULTS:**
THE IMPLEMENTATION OF SERIAL-IN-SERIAL-OUT-SHIFTREGISTER IS TESTED AND VERIFIED
