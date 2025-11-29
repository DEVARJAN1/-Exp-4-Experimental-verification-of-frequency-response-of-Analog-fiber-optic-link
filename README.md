
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="1189" height="704" alt="image" src="https://github.com/user-attachments/assets/4233a51c-fd16-49bc-bae6-64afbd48e4ad" />


## TABULATION  
**Transmission through Analog Link**

<img width="751" height="692" alt="image" src="https://github.com/user-attachments/assets/045e6595-33c6-4ae3-bb0e-b706db972e93" />

## MODEL GRAPH

<img width="1080" height="538" alt="image" src="https://github.com/user-attachments/assets/e8ac52a9-cc04-4f2c-bae9-1fc846b1463a" />

<img width="931" height="1240" alt="image" src="https://github.com/user-attachments/assets/ec9f6eac-93ff-4a51-91dc-ff62a7ec0d21" />


## RESULT

Thus, the frequency response of the analog fiber optic link was successfully studied, and the bandwidth was determined to be 95 kHz. (Summarize observations and conclusions here)
