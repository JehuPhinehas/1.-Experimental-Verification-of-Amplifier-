##**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/635c9837-d5f5-4d6f-acc9-8a47a4368230" />

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
<img width="1600" height="764" alt="image" src="https://github.com/user-attachments/assets/c24941b7-33fd-4c2b-8677-9574f70012e4" />




MODEL GRAPH 

<img width="1600" height="979" alt="image" src="https://github.com/user-attachments/assets/26bfd1d7-4bd3-4529-8a6b-9b6532ff2d3e" />


DESIGN:
<img width="1600" height="624" alt="image" src="https://github.com/user-attachments/assets/380cc4fe-747f-48e0-974f-d76e216b10ae" />



Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

<img width="1600" height="1283" alt="image" src="https://github.com/user-attachments/assets/7a12c6fb-5fd7-457f-8ae9-3e1a4f2d491f" />


---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="1079" height="1280" alt="image" src="https://github.com/user-attachments/assets/9449be4f-8fec-419c-8aec-1b21427c1a06" />




---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM

<img width="1600" height="754" alt="image" src="https://github.com/user-attachments/assets/84943f78-8254-4a0d-a38e-33d900d242b0" />




---

## MODEL GRAPH

<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/b33c3293-a0ed-439f-b833-220d57881d7c" />
## MODEL GRAPH

<img width="1600" height="503" alt="image" src="https://github.com/user-attachments/assets/b4ea70ec-f364-4fe3-829d-47f4a2ccd6fa" />

---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

<img width="1600" height="1065" alt="image" src="https://github.com/user-attachments/assets/8560bc70-793c-4cbb-8705-9317f1a167cd" />


---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="779" height="1280" alt="image" src="https://github.com/user-attachments/assets/a2f998a1-97f1-464c-8af9-e18f896fcee7" />





---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-28 at 11 05 00 AM](https://github.com/user-attachments/assets/dfb082df-3b02-44de-8b3b-29709eca318c)

## MODEL GRAPH
<img width="678" height="334" alt="image" src="https://github.com/user-attachments/assets/6aa1b9dd-b112-4be1-a37a-d5ee19607b1d" />

---
### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)
![WhatsApp Image 2025-11-28 at 11 05 13 AM](https://github.com/user-attachments/assets/ef9150ea-82b5-4d1a-81ee-13d3f4a10468)



---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-28 at 11 04 51 AM](https://github.com/user-attachments/assets/cb2415d6-7a91-49c7-a47b-6ec3fe35acc2)

---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER
![WhatsApp Image 2025-11-28 at 11 06 33 AM](https://github.com/user-attachments/assets/2ccb1077-8b0e-4cfe-aadf-74d3f7bfce1c)



PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)

![WhatsApp Image 2025-11-28 at 11 06 56 AM](https://github.com/user-attachments/assets/c2e31444-a58c-4d5a-8784-30ed1a57c955)

---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="1221" height="1280" alt="image" src="https://github.com/user-attachments/assets/ec5a8f68-3df5-4fcd-95ef-cb48621c61f7" />
76-8fda-480d-9c73-bd0f1b173610)



---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
