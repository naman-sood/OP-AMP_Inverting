# Op-Amp Inverting Amplifier Simulation  

## Overview  
This project demonstrates an **inverting amplifier** using the **LM741 operational amplifier** in **PSpice**. The circuit is simulated to observe voltage gain, phase inversion, and signal behavior.  

## Circuit Components  
- **Op-Amp:** LM741  
- **Resistors:**  
  - R1 = 1kΩ (Input Resistor)  
  - R2 = 10kΩ (Feedback Resistor)  
- **Power Supply:** ±12V DC  
- **Input Signal:** 500mV, 1kHz sine wave  

## Simulation Results  
- The circuit functions as an **inverting amplifier**, producing an output that is **180° out of phase** with the input.  
- The **gain (Av)** is given by:  
  \[
  Av = -\frac{R_f}{R_{in}} = -\frac{10kΩ}{1kΩ} = -10
  \]
- The waveform analysis confirms the expected behavior:  
  - The output amplitude is approximately **10 times** the input amplitude.  
  - The output is **inverted** compared to the input.  

## Software Used  
- **PSpice A/D Lite** for circuit simulation  
- **Cadence PSpice** for waveform analysis  

## How to Run the Simulation  
1. Open **PSpice A/D Lite** and load the circuit schematic.  
2. Set the input voltage to **500mV, 1kHz sine wave**.  
3. Run a **Transient Analysis** for at least **4ms**.  
4. Observe the **input and output waveforms** in the simulation window.  

## Output Waveforms  
- The first plot shows the **input signal (Vi)**.  
- The second plot shows the **output signal (Vo)**, which is **amplified and inverted**.  

## Conclusion  
This project demonstrates the working of an **inverting op-amp amplifier** with a gain of **-10**, confirming theoretical calculations. The simulation verifies the expected phase shift and voltage amplification.  

## Screenshots
![Screenshot 2025-02-22 145153](https://github.com/user-attachments/assets/5f73142a-d111-4b21-8055-4686a92b4a41)
![Screenshot 2025-02-22 145132](https://github.com/user-attachments/assets/0d287984-dbf2-480b-97fe-e75f2dbe6241)
