EESchema Schematic File Version 2
LIBS:adc-dac
LIBS:memory
LIBS:xilinx
LIBS:microcontrollers
LIBS:dsp
LIBS:microchip
LIBS:analog_switches
LIBS:motorola
LIBS:texas
LIBS:intel
LIBS:audio
LIBS:interface
LIBS:digital-audio
LIBS:philips
LIBS:display
LIBS:cypress
LIBS:siliconi
LIBS:opto
LIBS:atmel
LIBS:contrib
LIBS:power
LIBS:eSim_Plot
LIBS:transistors
LIBS:conn
LIBS:eSim_User
LIBS:regul
LIBS:74xx
LIBS:cmos4000
LIBS:eSim_Analog
LIBS:eSim_Devices
LIBS:eSim_Digital
LIBS:eSim_Hybrid
LIBS:eSim_Miscellaneous
LIBS:eSim_Power
LIBS:eSim_Sources
LIBS:eSim_Subckt
LIBS:eSim_Nghdl
LIBS:eSim_Ngveri
LIBS:eSim_SKY130
LIBS:eSim_SKY130_Subckts
LIBS:DC_To_DC_Converter-cache
EELAYER 25 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L eSim_Diode D1
U 1 1 633F0382
P 2700 2750
F 0 "D1" H 2700 2850 50  0000 C CNN
F 1 "eSim_Diode" H 2700 2650 50  0000 C CNN
F 2 "" H 2700 2750 60  0000 C CNN
F 3 "" H 2700 2750 60  0000 C CNN
	1    2700 2750
	0    -1   -1   0   
$EndComp
$Comp
L eSim_L L1
U 1 1 633F03EB
P 1350 2850
F 0 "L1" H 3300 3350 50  0000 C CNN
F 1 "10m" H 3300 3500 50  0000 C CNN
F 2 "" V 3300 3400 60  0000 C CNN
F 3 "" V 3300 3400 60  0000 C CNN
	1    1350 2850
	1    0    0    -1  
$EndComp
$Comp
L eSim_R R1
U 1 1 633F0486
P 5050 2650
F 0 "R1" H 5100 2780 50  0000 C CNN
F 1 "10" H 5100 2600 50  0000 C CNN
F 2 "" H 5100 2630 30  0000 C CNN
F 3 "" V 5100 2700 30  0000 C CNN
	1    5050 2650
	0    1    1    0   
$EndComp
$Comp
L eSim_C C1
U 1 1 633F04E0
P 4500 2700
F 0 "C1" H 4525 2800 50  0000 L CNN
F 1 "220u" H 4525 2600 50  0000 L CNN
F 2 "" H 4538 2550 30  0000 C CNN
F 3 "" H 4500 2700 60  0000 C CNN
	1    4500 2700
	1    0    0    -1  
$EndComp
Wire Wire Line
	2150 2300 3000 2300
Wire Wire Line
	2700 2300 2700 2600
Connection ~ 2700 2300
Wire Wire Line
	3600 2300 4500 2300
Wire Wire Line
	4500 2300 4500 2550
Wire Wire Line
	5100 2550 5100 2300
Wire Wire Line
	5100 2300 4450 2300
Connection ~ 4450 2300
Wire Wire Line
	2700 2900 2700 3100
Wire Wire Line
	2700 3100 5100 3100
Wire Wire Line
	5100 3100 5100 2850
Wire Wire Line
	4500 2850 4500 3100
Connection ~ 4500 3100
Wire Wire Line
	1200 2400 1200 2300
Wire Wire Line
	1200 2300 1750 2300
$Comp
L GND #PWR01
U 1 1 633F0B47
P 1200 3300
F 0 "#PWR01" H 1200 3050 50  0001 C CNN
F 1 "GND" H 1200 3150 50  0000 C CNN
F 2 "" H 1200 3300 50  0001 C CNN
F 3 "" H 1200 3300 50  0001 C CNN
	1    1200 3300
	1    0    0    -1  
$EndComp
$Comp
L pulse v2
U 1 1 633F0C92
P 2850 4100
F 0 "v2" H 2650 4200 60  0000 C CNN
F 1 "pulse" H 2650 4050 60  0000 C CNN
F 2 "R1" H 2550 4100 60  0000 C CNN
F 3 "" H 2850 4100 60  0000 C CNN
	1    2850 4100
	1    0    0    -1  
$EndComp
Wire Wire Line
	2350 2800 2350 3500
Wire Wire Line
	2850 3650 2850 3500
Connection ~ 2850 3500
$Comp
L GND #PWR02
U 1 1 633F0D7F
P 2850 4550
F 0 "#PWR02" H 2850 4300 50  0001 C CNN
F 1 "GND" H 2850 4400 50  0000 C CNN
F 2 "" H 2850 4550 50  0001 C CNN
F 3 "" H 2850 4550 50  0001 C CNN
	1    2850 4550
	1    0    0    -1  
$EndComp
Text GLabel 1050 2350 0    60   Input ~ 0
In
Text GLabel 5250 2350 2    60   Output ~ 0
out
Wire Wire Line
	5250 2350 5100 2350
Connection ~ 5100 2350
Wire Wire Line
	1050 2350 1200 2350
Connection ~ 1200 2350
Wire Wire Line
	2850 3500 2350 3500
$Comp
L plot_v1 U2
U 1 1 633F1A53
P 5000 2300
F 0 "U2" H 5000 2800 60  0000 C CNN
F 1 "plot_v1" H 5200 2650 60  0000 C CNN
F 2 "" H 5000 2300 60  0000 C CNN
F 3 "" H 5000 2300 60  0000 C CNN
	1    5000 2300
	1    0    0    -1  
$EndComp
Wire Wire Line
	5000 2100 5000 2300
Wire Wire Line
	5000 2300 4950 2300
Connection ~ 4950 2300
$Comp
L plot_v1 U1
U 1 1 633F1B47
P 1100 2550
F 0 "U1" H 1100 3050 60  0000 C CNN
F 1 "plot_v1" H 1300 2900 60  0000 C CNN
F 2 "" H 1100 2550 60  0000 C CNN
F 3 "" H 1100 2550 60  0000 C CNN
	1    1100 2550
	1    0    0    -1  
$EndComp
Text GLabel 2650 3650 0    60   Input ~ 0
pulse
Wire Wire Line
	2650 3650 2850 3650
Wire Wire Line
	1950 2800 2350 2800
$Comp
L DC v1
U 1 1 633F2383
P 1200 2850
F 0 "v1" H 1000 2950 60  0000 C CNN
F 1 "DC" H 1000 2800 60  0000 C CNN
F 2 "R1" H 900 2850 60  0000 C CNN
F 3 "" H 1200 2850 60  0000 C CNN
	1    1200 2850
	1    0    0    -1  
$EndComp
Wire Wire Line
	1950 2800 1950 2600
$Comp
L eSim_MOS_P M1
U 1 1 633F17BA
P 1950 2150
F 0 "M1" H 1900 2200 50  0000 R CNN
F 1 "eSim_MOS_P" H 2000 2300 50  0000 R CNN
F 2 "" H 2200 2250 29  0000 C CNN
F 3 "" H 2000 2150 60  0000 C CNN
	1    1950 2150
	0    1    1    0   
$EndComp
Wire Wire Line
	1950 2600 2350 2600
Wire Wire Line
	2350 2600 2350 1650
Wire Wire Line
	2350 1650 1950 1650
Wire Wire Line
	1950 1650 1950 2000
$Comp
L DC v3
U 1 1 633F19EF
P 1050 1650
F 0 "v3" H 850 1750 60  0000 C CNN
F 1 "DC" H 850 1600 60  0000 C CNN
F 2 "R1" H 750 1650 60  0000 C CNN
F 3 "" H 1050 1650 60  0000 C CNN
	1    1050 1650
	0    1    1    0   
$EndComp
Wire Wire Line
	1500 1650 1500 2400
Wire Wire Line
	1500 2400 1800 2400
$Comp
L GND #PWR03
U 1 1 633F1A89
P 600 1650
F 0 "#PWR03" H 600 1400 50  0001 C CNN
F 1 "GND" H 600 1500 50  0000 C CNN
F 2 "" H 600 1650 50  0001 C CNN
F 3 "" H 600 1650 50  0001 C CNN
	1    600  1650
	1    0    0    -1  
$EndComp
$EndSCHEMATC
