# DC-to-DC-Buck-Converter-



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
This paper presents the literature survey of system on chip mixed signal controller for DC-DC converter circuit to be implemented by e-Sim. 

## Introduction:-
The DC-DC converter is widely used power electronic circuit used in electronic circuit. Its application involve in small devices like portable devices, wearable devices, IoTs, and electric vehicle, chargeable-battery charger. All these devices requires efficient power supply; which is not possible by LDOs (Low-Dropout Regulator); at the specified voltage level. So, it can be designed with proper selection of controller. Mixed signal controller is also a vital option after analog controller and digital controller, as it will provide greater stability in terms of regulated output voltages. The advantage of digital converter is that it has inherent noise immunity and analog implementations provides inherent current protection, simple/robust compensation and reduced audio susceptibility [1].

Figure 1 shows the block diagram of typical DC-DC converter designed to operate in closed loop system. Where the output regulated voltage is occurred by switching of the switching devices in DC-DC converter. The desired value is adjusted with the reference value, which is compared with the feedback value to generate the error signal and then further processed to generate the controlling signal. 
The designing of efficient controller is a crucial task for electronic engineers. The feedback signal is sensed with then converted into digital values by A/D converter. The digital comparator used to compare the value with reference values. The generated error signal after comparison is processed through PI controller [2] and then is generated the controlled signal of desired switching frequency.  
The analog to digital converter, digital comparator, analog comparator, digital to analog converter (DAC), ramp generator, clock generator, flip flop, switch will be used in single, However inductor and capacitor will be connected externally.



## Circuit Details:

The block diagram of typical DC-DC converter designed to operate in closed loop system. Where the output regulated voltage is occurred by switching of the switching devices in DC-DC converter. The desired value is adjusted with the reference value, which is compared with the feedback value to generate the error signal and then further processed to generate the controlling signal. 

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

![image](https://user-images.githubusercontent.com/115182557/194390313-bd7fe94a-0a5e-4eb4-aaae-9bde910455ed.png)



## Waveforms
![image](https://user-images.githubusercontent.com/115182557/194390343-cd214e17-a071-448d-964c-83056908b525.png)





## Acknowlegdements:
1. FOSSEE, IIT Bombay
2. Steve Hoover, Founder, Redwood EDA
3. Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd. - kunalpghosh@gmail.com
4. Sumanto Kar, eSim Team, FOSSEE

## References
[1] O. Trescases, Z. Lukic, N. Wai Tung and A. Prodic, "A low-power mixed-signal current-mode DC-DC converter using a one-bit Delta Sigma DAC", Proc. 21st Annu. IEEE Appl. Power Electron. Conf. Expo., 2006.
[2] Choi, Y.; Chang, N.; Kim, T. DC–DC converter-aware power management for low-power embedded systems. IEEE Trans. Comput. Aided Des. Integr. Circ. Syst. 2007, 26, 8.

