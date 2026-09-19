# DSB-SC-AM-MODULATOR-AND-DEMODULATOR-USING-SCILAB

## AIM

To write a program to perform DSBSC modulation and demodulation using SCI LAB and study its spectral characteristics.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

> **Note:** Keep all the switch faults in off position.

---

## ALGORITHM

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the message signal.
* **Amplitude:** Maximum amplitude of the message signal.

### 2. Generate Signals:

* **Message Signal:** A sinusoidal signal that will be modulated.
* **Carrier Signal:** A high-frequency sinusoidal signal used for modulation.

### 3. DSBSC Modulation:

* **Modulated Signal:** Multiply the message signal by the carrier signal to produce the DSBSC signal.

### 4. DSBSC Demodulation:

* **Multiplication:** Multiply the modulated signal by the carrier signal to get the product of the message signal with itself (i.e., the original message signal plus high-frequency components).
* **Low-pass Filtering:** Apply a Butterworth low-pass filter to remove the high-frequency components and recover the original message signal.

### 5. Visualization:

Plot the message signal, carrier signal, DSBSC modulated signal, and the recovered signal after demodulation.

---

## PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.

---

## TABULATION

<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/d38e0bf2-6531-4430-8d29-4e2f87a57d9c" />
<img width="1599" height="899" alt="image" src="https://github.com/user-attachments/assets/097db54a-9cb6-4b8d-bf34-03c4ec655c1e" />



## MODEL GRAPH
<img width="1010" height="973" alt="WhatsApp Image 2026-09-18 at 21 12 09" src="https://github.com/user-attachments/assets/e4d0362d-0be2-4c9f-9a29-269d23f2b8ba" />

## Output
<img width="1599" height="899" alt="image" src="https://github.com/user-attachments/assets/478357ea-433c-463b-a853-390453d03a10" />

## Result
Successfully performed DSBSC modulation and demodulation using SCI LAB .


