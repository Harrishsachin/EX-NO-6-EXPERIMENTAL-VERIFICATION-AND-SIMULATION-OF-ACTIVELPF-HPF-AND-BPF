# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP
            
**DATE:**  
         
---

## AIM
            
**DATE:**  
         
---

## AIM and obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter

---

** 6 A :- LOW PASS FILTER**



## THEORY
## LOW PASS FILTER
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.
## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |

---
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-29 at 08 01 14_2bf9dc38](https://github.com/user-attachments/assets/4f87f4df-73f8-4249-b6fd-3a2e3ab16da5)
![WhatsApp Image 2025-11-29 at 08 02 41_636f9ae8](https://github.com/user-attachments/assets/d1e21ddd-4f5a-4f35-b0ce-4bc5239b04b0)




## MODEL GRAPH

![WhatsApp Image 2025-11-29 at 08 03 45_0d601c9b](https://github.com/user-attachments/assets/15d2394e-3e06-48e5-9bea-5b9ff1d4e23f)



## DESIGN

<img width="1412" height="1600" alt="image" src="https://github.com/user-attachments/assets/19a8c94c-d0dc-4ff0-8a10-caafb07b4070" />



## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-11-29 at 08 04 25_e81f8944](https://github.com/user-attachments/assets/9bdaca6c-a829-4071-a9a7-73a26d33f210)



		

---

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="1093" height="620" alt="Screenshot 2025-11-29 080435" src="https://github.com/user-attachments/assets/dd3614ea-adf4-463b-9f20-ce01f1bd1b72" />

![WhatsApp Image 2025-11-29 at 08 05 52_7316b824](https://github.com/user-attachments/assets/1757c40e-4284-46e7-b723-45fc2d4c7ae0)




 ## 6 B HIGH PASS FILTER

---

## THEORY
HIGH PASS FILTER
A HPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,5.86K, 0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-29 at 08 06 49_c7066522](https://github.com/user-attachments/assets/baa0e24d-8bac-444b-9ea4-bcc16af23206)
![WhatsApp Image 2025-11-29 at 08 07 25_d5846057](https://github.com/user-attachments/assets/d8585c73-c84d-4a5a-b6c2-4b36c6f149c9)




## MODEL GRAPH

![WhatsApp Image 2025-11-29 at 08 08 28_7d301269](https://github.com/user-attachments/assets/4578eaf3-b8c3-4f2f-9c80-b154b4c7d79a)

---

## DESIGN

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-11-29 at 08 08 52_b2c88aad](https://github.com/user-attachments/assets/3ef723b1-0086-42d2-bb4b-9a000442ab9f)


---

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="1077" height="607" alt="Screenshot 2025-11-29 080850" src="https://github.com/user-attachments/assets/d2ff5de8-9108-4a30-b925-67c84da0f405" />

![WhatsApp Image 2025-11-29 at 08 09 40_7b193df1](https://github.com/user-attachments/assets/62bb500b-ad73-4e48-9315-4af2d3b2b05f)



 ## 6C Band Pass Filter

---

## THEORY
 ##Band Pass Filter
A BPF allows frequencies in between lower cut of frequency and higher cut of frequency, fH-fL. A band-pass (BP) filter passes frequencies in a band fL_fH and attenuates below fL and above fH.. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |10K,38.8K,7.9K,0.01uf | 1 |
| 7 | Connecting ires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-29 at 08 11 22_b1281e15](https://github.com/user-attachments/assets/6d36d0bf-e3d9-427f-94f5-70d5b99efeb6)
![WhatsApp Image 2025-11-29 at 08 11 52_53c081e6](https://github.com/user-attachments/assets/57ef70dd-592c-4c54-a619-28fef4482050)



## MODEL GRAPH

![WhatsApp Image 2025-11-29 at 08 12 47_7c386d67](https://github.com/user-attachments/assets/14bc88a6-c101-469d-8981-b3119d773c0d)


---

## DESIGN

DESIGN: BAND PASS FILTER

Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.
1.	Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency of HPF as fL = 1 KHz.
2.	Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf. Let C = 0.1μf.
3.	Calculate R from the expression. Given: fH = 2KHz = 1/ (2πR1C1) Let C1 = 0.1 µF, R1 = 7.9 KΩ
Given: fL = 400Hz = 1/ (2πR2C2)
Let C2 = 0.1 µF, R2 = 39.8 KΩ
Pass band Gain=4
Now		Ao = 1 + (Rf / R1) 2-1=(Rf / Ri)
Ri = Rf
Let Ri = Rf = 10 KΩ


## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-11-29 at 08 13 43_8e2dbb77](https://github.com/user-attachments/assets/faa1e753-d53b-421c-96fb-557ef033dea4)


---

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="1061" height="487" alt="Screenshot 2025-11-29 081316" src="https://github.com/user-attachments/assets/6f3e3a90-f2f7-485f-b73d-15dfabf6f996" />

![WhatsApp Image 2025-11-29 at 08 14 06_cd8965fc](https://github.com/user-attachments/assets/feeb469d-9349-4ed3-9ef6-0a6b613561df)


---
##RESULT:
	![WhatsApp Image 2025-11-29 at 08 14 34_f4534fd3](https://github.com/user-attachments/assets/fb9f345d-fe24-4801-8be5-4db917b2deda)

   
