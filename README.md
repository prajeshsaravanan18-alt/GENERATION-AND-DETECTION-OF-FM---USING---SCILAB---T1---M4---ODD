# GENERATION-AND-DETECTION-OF-FM---USING---SCILAB---T1---M4---ODD
# FREQUENCY MODULATION AND DEMODULATION

## AIM

To write a program for Frequency Modulation and Demodulation using SCILAB and to observe and measure the frequency deviation and the modulation index of FM.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

---

## THEORY

Frequency modulation is a type of modulation in which the frequency of the high frequency (carrier) is varied in accordance with the instantaneous value of the modulating signal.

### FREQUENCY DEVIATION Δf and MODULATION INDEX mf:

The frequency deviation **Δf** represents the maximum shift between the modulated signal frequency, over and under the frequency of the carrier.

We define modulation index **mf** the ratio between **Δf** and the modulating frequency.

$$
m_f = \frac{\Delta f}{f_m}
$$

---

## FREQUENCY MODULATION GENERATION

The circuits used to generate a frequency modulation must vary the frequency of a high frequency signal (carrier) as function of the amplitude of a low frequency signal (modulating signal). In practice there are two main methods used to generate FM.

---

## ALGORITHM

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the modulating signal.
* **Beta:** Modulation index, which controls the extent of frequency deviation.

### 2. Generate Signals:

* **modulating_signal:** Sinusoidal signal used for modulation.
* **carrier_signal:** The high-frequency carrier signal.
* **modulated_signal:** FM modulated signal calculated by varying the carrier frequency according to the modulating signal.

### 3. FM Modulation:

* **Modulated_signal** is obtained by modulating the carrier signal with the modulating signal.

### 4. FM Demodulation:

* **Differentiation:** Computes the derivative of the modulated signal to extract frequency variations.
* **Envelope Detection:** Takes the absolute value to retrieve the envelope of the signal.
* **Low-pass Filtering:** Applies a Butterworth low-pass filter to smooth the envelope and recover the original modulating signal.

### 5. Visualization:

* Plots the modulating signal, carrier signal, FM modulated signal, and demodulated signal for analysis.

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
##  PROGRAM
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/233977ae-c35b-498a-b6db-3e27d53b5d51" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/76fe7988-3682-4f5e-8b92-19f660836340" />

## TABULATION 
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/cdbaa73a-db07-4f23-a288-95221221a80c" />

## CALCULATION
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/9f92e0f2-b3de-4554-8dfa-6a53af21f2df" />

## MODEL GRAPH
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/d8aaa80a-5f5d-4e7a-8280-28fa2de8c6e5" />
## MARK SPLIT UP
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/81fb2055-340e-4fbc-a98d-6f3993c60c16" />



