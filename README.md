Signal monitoring and analysis part with MATLAB:
At this stage of the project, we focus on processing the acoustic signals collected from the body during the initial phase. The raw sound signals acquired by the stethoscope are filtered within a specific frequency range to reduce noise and amplified to enhance their strength. In this phase, continuous analog signals are converted into digital format. This digital conversion process is carried out using an Arduino microcontroller.

Digital Conversion Process:
Using Arduino's analog input pins signals from the body are converted into voltage levels. Arduino then translates these analog voltage signals into digital values. These values are processed in a format readable by MATLAB or similar platforms. To facilitate further analysis and visualization, a GUI (Graphical User Interface) is developed in MATLAB.

Filtering and Spectrum Analysis: 
The collected digital signals undergo filtering in MATLAB to retain the desired frequency bands, while limiting the impact of the undesired noise. High-pass and low-pass filters are separately applied to capture most of the heart sounds, respiratory sounds, and all other internal body sounds. The FFT (Fast Fourier Transform) method is used for spectral analysis of the signals. The analysis allows for simultaneous display of raw and filtered signal spectra.

Real-Time Visualization:
The MATLAB GUI allows real-time monitoring of the signals. Users can manually adjust filter settings and observe sound signals within different frequency ranges. This process enables direct graphical monitoring of parameters such as heart rate and respiration rate.

Matlab app design:
![image](https://github.com/user-attachments/assets/75fe6bdb-0f70-45fc-948d-796ad87b5798)
