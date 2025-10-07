# DSBSC


EX NO: 2	DSB-SC-AM MODULATOR AND DEMODULATOR

AIM:

To write a program to perform DSBSC modulation and demodulation using SCI LAB and study its spectral characteristics

EQUIPMENTS REQUIRED

•	Computer with i3 Processor
•	SCI LAB

Note: Keep all the switch faults in off position

Algorithm:

1.	Define Parameters:
•	Fs: Sampling frequency.
•	T: Duration of the signal.
•	Fc: Carrier frequency.
•	Fm: Frequency of the message signal.
•	Amplitude: Maximum amplitude of the message signal.
2.	Generate Signals:
•	Message Signal: A sinusoidal signal that will be modulated.
•	Carrier Signal: A high-frequency sinusoidal signal used for modulation.
3.	DSBSC Modulation:
•	Modulated Signal: Multiply the message signal by the carrier signal to produce the DSBSC signal.
4.	DSBSC Demodulation:
•	Multiplication: Multiply the modulated signal by the carrier signal to get the product of the message signal with itself (i.e., the original message signal plus high-frequency components).
•	Low-pass Filtering: Apply a Butterworth low-pass filter to remove the high- frequency components and recover the original message signal.
5.	Visualization:
Plot the message signal, carrier signal, DSBSC modulated signal, and the recovered signal after demodulation.
PROCEDURE

•	Refer Algorithms and write code for the experiment.
•	Open SCILAB in System
•	Type your code in New Editor
•	Save the file
 
•	Execute the code
•	If any Error, correct it in code and execute again
•	Verify the generated waveform using Tabulation and Model Waveform

Model Waveform

<img width="703" height="679" alt="image" src="https://github.com/user-attachments/assets/e7c7c7f8-ccf2-41ac-b1f3-325989941a6f" />

Program

<img width="712" height="646" alt="image" src="https://github.com/user-attachments/assets/185dfd11-f69b-4f3e-9e53-90c89479c145" />


Output Graph

<img width="1539" height="976" alt="image" src="https://github.com/user-attachments/assets/565f20b8-521d-4ff9-91a2-0cbb833c2a25" />



Tablular Column

![WhatsApp Image 2025-10-07 at 20 44 50_cf255e7a](https://github.com/user-attachments/assets/64a794a3-7d7c-48bd-a517-5a9fe9f07623)

![WhatsApp Image 2025-10-07 at 20 44 51_f58a00fd](https://github.com/user-attachments/assets/f5baff1b-0837-407d-bfb6-fbb95cea3b48)



Result

Thus the DSB-SC-AM Modulation and Demodulation is generated.

