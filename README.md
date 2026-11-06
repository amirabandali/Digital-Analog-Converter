# 3-Bit Binary Weighted R-2R-4R Digital Analog Converter (DAC)

## Overview
This a design, creation, and simulated implementation of a 3-bit binary weighted R-2R-4R digital analog converter (DAC). The circuit translates 3 bit inputs into corresponding analog voltage levels through 2 operational amplifiers, one that converts the digital inputs to analog and another that inverts the sign. This was created using the Analog Discovery 3 kit and the WaveForms application.

---

## Circuit Schematic


---

## Binary to Analog Conversion Values
Mapping of 3-bit digital codes to ideal analog voltages:

<img width="807" height="405" alt="image" src="https://github.com/user-attachments/assets/e8378caf-1884-4ced-ae74-b746cde754df" />


---

Deriving Vout Formula:

<img width="1536" height="2132" alt="unnamed" src="https://github.com/user-attachments/assets/89f07695-35a5-438e-9d5d-3d5957d87429" />

---

## Circuit Wiring
<img width="3894" height="3000" alt="20261031_213613" src="https://github.com/user-attachments/assets/9bc018aa-441f-4685-904b-37df2dbd449e" />

---

## Digital Input
The WaveForms Pattern Generator was used to configure the 3 digital I/O pins as inputs and produce clock pulses at 250 Hz, 500 Hz, and 1 kHz frequencies. This allows the signals from these pins to be sensed and plotted with the oscilloscope feature to present the analog output voltage waveforms:

<img width="1157" height="600" alt="image" src="https://github.com/user-attachments/assets/7ae80389-b1ed-4f50-91d6-ab79bc815e4c" />

---

The WaveForms application also shows the input voltage supplied from the Analog Discovery 3 which can be seen here (-5V to 5V):

<img width="1157" height="597" alt="image" src="https://github.com/user-attachments/assets/0e5cd7b9-a100-4287-8612-6ca85ebe326d" />

---

## Oscilliscope Output
These are the analog voltage output waveforms from the circuit:

<img width="1852" height="987" alt="Screenshot 2026-10-31 213325" src="https://github.com/user-attachments/assets/cf3d4c07-580a-442f-9cf1-dfe4d5041561" />

---

<img width="1127" height="496" alt="image" src="https://github.com/user-attachments/assets/8239a9ca-976d-4f44-9226-3e465f304235" />


---
