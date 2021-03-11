# HKUST-OWL-Co-simulation-Platform
Supervised by Professor C. Patrick Yue, We developed this co-simulation platform for high frequency RF and mm-Wave transceiver systems dealing with complex modulated signals

# 1. Motivation

Traditionally, a continuous-wave (CW) signal is used to evaluate and simulate RF and millimeter-wave (mm-wave) circuits during the design procedure, while fabricated circuits are measured by modulated signals in the test phase, because complex modulated signals are used in reality. It is almost impossible to use a CW signal to predict system performance, such as error vector magnitude (EVM), bit error rate (BER), etc., of RF and mm-wave circuits when dealing with complex modulated signals. This platform is used for radio frequency system simulation. MATLAB is used to simlulate the baseband part of the system. The signal with both single or multi subcarries can be generated by the MATLAB code with adjustable parameters. The generated signal can be transmitted to ADS or cadence as the input of the frontend circuit. Then the simulation result from ADS or cadence is returned to MATLAB again for decoding and demodulation. The constellation, signal spectrum and waveform in time domain from both transmitter and receiver can be obtained. And the peak to average power ratio, bit error rate can be calculated automatically by the simulator. The structure and the usage of the simulator is shown below.

<img src="Pictures/Platform_Usefull.png" width="600">

