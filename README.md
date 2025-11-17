# DSP_L4
Fourier transform exercises

Basic signal generation \
The magnitude spectrum shows the positive and negative portions of the sine wave
### 4.6
<img width="1766" height="1164" alt="Screenshot 2025-09-24 at 15 25 46" src="https://github.com/user-attachments/assets/adf82e4b-7b25-4321-b796-305053fc3ad7" />

___________  


A more complex signal is plotted, created by addig two signals together  
The magnitude spectrum shows the frequency of the two constituent sine waves 
### 4.7
<img width="1766" height="1170" alt="Screenshot 2025-09-24 at 15 26 06" src="https://github.com/user-attachments/assets/7fb00abd-97a7-4ef7-ac20-5a697fb40eac" />  

__________  


A time vector od 10 seconds is created  
A composite sine wave consiting of 2 frequencies is generated  
The symmetrical frequencies are visible at 15, 40, 60 and 85  
he phase shit plot shows how each frequency component is shifted in time
### 4.8
<img width="1766" height="1174" alt="Screenshot 2025-09-24 at 15 26 23" src="https://github.com/user-attachments/assets/cfb7c50e-4c10-4fa9-91a8-5e4a2bd3fc11" />   

_________  


Frquency resolution is changed to 512, instead of 1000 as seen above  
This has a dramatic effect on the phase plot  
Because 512 does not match the original signal length, MATLAB must:

truncate the signal if x is longer

zero-pad the signal if x is shorter

This introduces spectral leakage, which affects phase a lot
### 4.9
<img width="1766" height="1162" alt="Screenshot 2025-09-24 at 15 26 36" src="https://github.com/user-attachments/assets/34578df9-4867-45c2-b67a-6b0d9981503c" />
