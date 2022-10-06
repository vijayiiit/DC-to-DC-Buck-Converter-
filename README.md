# DC-to-DC-Buck-Converter-
# Implementation-of-Digital-Phase-Locked-Loop-using-CMOS-Technology


- [Abstract](#abstract)
- [Reference Circuit Diagram](#reference-circuit-diagram)
- [Circuit Details](#circuit-details)
- [Software Used](#software-used)
    * [eSim](#esim)
    * [NgSpice](#ngspice)
    * [Makerchip](#makerchip)
- [Circuit Diagram in eSim](#circuit-diagram-in-esim)
- [Waveforms](#waveforms)
     * [Transient Response](#Transient-Response)
  
   
  
- [Acknowlegdements](#acknowlegdements)
- [References](#references)
 
## Abstract:- 
The requirement for low power and rapid circuits
are expanding in present day hardware. The generation of carrier
and locking of phase have become significant for transceiver
circuits. The frequency divider which is dependent on the phase
locked loop (PLL) is a fundamental building block of the
transceiver. The frequency divider that produces the carrier for the
down-conversion/up-conversion functions, it works at high
frequency and it expends a massive portion of the whole power of
the circuit. The frequency divider dependent on phase locked loop
(PLL) comprises voltage controlled oscillator (VCO), phase
detector, loop filter and frequency divider.

## Introduction:-
A phase lock loop is a negative feedback system consisting of a
phase detector, low pass filter and voltage controlled oscillator
(VCO). Its purpose is to synchronize an output signal with a
reference or input signal in frequency as well as in phase.
Classification of PLL is Analog PLL Digital PLL and All digital
PLL The major application of PLL is frequency synthesis for
frequency multiplier and frequency divider. In frequency synthesis,
If we want 1Ghz from the 100 Mhz reference voltage so there we
use PLL. and Also used in clock data recovery data[1].



## Reference Block Diagram:
![image](https://user-images.githubusercontent.com/98162318/194290687-d9e50c83-46c3-4ad8-ba10-e40014f2dcd3.png)




## Circuit Details:

Applied to the Phase detector. In a phase detector there are two
input signals one is a reference signal or input signal and the
second is a feedback signal or an output of the oscillator signal.
Phase detector is basically a comparator circuit that compares both
the input and the output to detect the phase difference between
input signal and feedback signal. Means output of the phase
detector is an error voltage that is proportional to the phase
difference between input signal and oscillator frequency[2].

## Software Used:
### eSim
It is an Open Source EDA developed by FOSSEE, IIT Bombay. It is used for electronic circuit simulation. It is made by the combination of two software namely NgSpice and KiCAD.
For more details refer:

https://esim.fossee.in/home

### NgSpice
It is an Open Source Software for Spice Simulations. For more details refer:

http://ngspice.sourceforge.net/docs.html

### Makerchip
It is an Online Web Browser IDE for Verilog/System-verilog/TL-Verilog Simulation. Refer

https://www.makerchip.com/

### Verilator
It is a tool which converts Verilog code to C++ objects. Refer:

https://www.veripool.org/verilator/

### Circuit Diagram in eSim:

![image](https://user-images.githubusercontent.com/98162318/194295075-6e8c2ab7-bcfc-4937-b2fa-66ecb0261f04.png)


## Waveforms

![PLL_Output](https://user-images.githubusercontent.com/98162318/194319677-8d7006bc-11ed-44cb-b077-9427186ef2ac.png)



## Acknowlegdements:
1. FOSSEE, IIT Bombay
2. Steve Hoover, Founder, Redwood EDA
3. Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd. - kunalpghosh@gmail.com
4. Sumanto Kar, eSim Team, FOSSEE

## References
[1] Kishore, P., et al. "Implementation of Digital
Phase Locked Loop using CMOS Technology."
2021 International Conference on Advances in
Electrical, Computing, Communication and
Sustainable Technologies (ICAECT). IEEE,
2021.

[2] Akhter, Nargis, and Md Tawfiq Amin. "An area efficient low power Phase-Frequency Detector for PLL Applications." 2020 2nd International Conference on Advanced Information and Communication Technology (ICAICT). IEEE, 2020
