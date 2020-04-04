EESchema Schematic File Version 4
LIBS:SQX_MOD-cache
EELAYER 26 0
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
L MCU_Microchip_ATmega:ATmega1284P-AU U1
U 1 1 5E849067
P 3400 2950
F 0 "U1" H 3400 864 50  0000 C CNN
F 1 "ATmega1284P-AU" H 3400 773 50  0000 C CNN
F 2 "Package_QFP:TQFP-44_10x10mm_P0.8mm" H 3400 2950 50  0001 C CIN
F 3 "http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-8272-8-bit-AVR-microcontroller-ATmega164A_PA-324A_PA-644A_PA-1284_P_datasheet.pdf" H 3400 2950 50  0001 C CNN
	1    3400 2950
	1    0    0    -1  
$EndComp
$Comp
L Device:C_Small C_clock1
U 1 1 5E8496E3
P 2050 1400
F 0 "C_clock1" V 1821 1400 50  0000 C CNN
F 1 "22pf" V 1912 1400 50  0000 C CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" H 2050 1400 50  0001 C CNN
F 3 "~" H 2050 1400 50  0001 C CNN
	1    2050 1400
	0    1    1    0   
$EndComp
$Comp
L Device:C_Small C_clock2
U 1 1 5E849762
P 2050 1700
F 0 "C_clock2" V 1821 1700 50  0000 C CNN
F 1 "22pf" V 1912 1700 50  0000 C CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" H 2050 1700 50  0001 C CNN
F 3 "~" H 2050 1700 50  0001 C CNN
	1    2050 1700
	0    1    1    0   
$EndComp
Wire Wire Line
	1950 1400 1900 1400
$Comp
L power:GND #PWR01
U 1 1 5E8499A7
P 1900 1750
F 0 "#PWR01" H 1900 1500 50  0001 C CNN
F 1 "GND" H 1905 1577 50  0000 C CNN
F 2 "" H 1900 1750 50  0001 C CNN
F 3 "" H 1900 1750 50  0001 C CNN
	1    1900 1750
	1    0    0    -1  
$EndComp
Wire Wire Line
	1900 1750 1900 1700
$Comp
L Interface_USB:CP2102N-A01-GQFN24 U3
U 1 1 5E849D1B
P 7350 1800
F 0 "U3" H 7350 2878 50  0000 C CNN
F 1 "CP2102N-A01-GQFN24" H 7350 2787 50  0000 C CNN
F 2 "Package_DFN_QFN:QFN-24-1EP_4x4mm_P0.5mm_EP2.6x2.6mm" H 7800 1000 50  0001 L CNN
F 3 "http://www.silabs.com/support%20documents/technicaldocs/cp2102n-datasheet.pdf" H 7400 750 50  0001 C CNN
	1    7350 1800
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR05
U 1 1 5E849F6D
P 3550 4950
F 0 "#PWR05" H 3550 4700 50  0001 C CNN
F 1 "GND" H 3555 4777 50  0000 C CNN
F 2 "" H 3550 4950 50  0001 C CNN
F 3 "" H 3550 4950 50  0001 C CNN
	1    3550 4950
	1    0    0    -1  
$EndComp
Wire Wire Line
	3400 4950 3550 4950
$Comp
L power:+5V #PWR04
U 1 1 5E84ACCE
P 3500 700
F 0 "#PWR04" H 3500 550 50  0001 C CNN
F 1 "+5V" H 3515 873 50  0000 C CNN
F 2 "" H 3500 700 50  0001 C CNN
F 3 "" H 3500 700 50  0001 C CNN
	1    3500 700 
	1    0    0    -1  
$EndComp
$Comp
L Device:C_Small C_power1
U 1 1 5E84AF1C
P 3300 800
F 0 "C_power1" V 3071 800 50  0000 C CNN
F 1 "100nF" V 3162 800 50  0000 C CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" H 3300 800 50  0001 C CNN
F 3 "~" H 3300 800 50  0001 C CNN
	1    3300 800 
	0    1    1    0   
$EndComp
Wire Wire Line
	3400 950  3400 800 
Wire Wire Line
	3400 800  3400 700 
Wire Wire Line
	3400 700  3500 700 
Connection ~ 3400 800 
Wire Wire Line
	3200 800  3150 800 
Wire Wire Line
	3150 800  3150 850 
$Comp
L power:GND #PWR03
U 1 1 5E84B369
P 3150 850
F 0 "#PWR03" H 3150 600 50  0001 C CNN
F 1 "GND" H 3155 677 50  0000 C CNN
F 2 "" H 3150 850 50  0001 C CNN
F 3 "" H 3150 850 50  0001 C CNN
	1    3150 850 
	1    0    0    -1  
$EndComp
$Comp
L Device:R RReset1
U 1 1 5E84C033
P 2500 1050
F 0 "RReset1" V 2293 1050 50  0000 C CNN
F 1 "10K" V 2384 1050 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" V 2430 1050 50  0001 C CNN
F 3 "~" H 2500 1050 50  0001 C CNN
	1    2500 1050
	0    1    1    0   
$EndComp
Wire Wire Line
	2650 1050 2650 1150
Wire Wire Line
	2650 1250 2800 1250
Connection ~ 2650 1150
Wire Wire Line
	2650 1150 2650 1250
$Comp
L power:+5V #PWR02
U 1 1 5E84C53B
P 2350 900
F 0 "#PWR02" H 2350 750 50  0001 C CNN
F 1 "+5V" H 2365 1073 50  0000 C CNN
F 2 "" H 2350 900 50  0001 C CNN
F 3 "" H 2350 900 50  0001 C CNN
	1    2350 900 
	1    0    0    -1  
$EndComp
Wire Wire Line
	2350 900  2350 1050
Wire Wire Line
	6000 1900 6350 1900
Wire Wire Line
	6600 1900 6600 2100
Wire Wire Line
	6600 2100 6750 2100
$Comp
L Device:D_TVS D_CP1
U 1 1 5E84EC1E
P 6350 2250
F 0 "D_CP1" V 6304 2329 50  0000 L CNN
F 1 "D_TVS" V 6395 2329 50  0000 L CNN
F 2 "Diode_SMD:D_0201_0603Metric" H 6350 2250 50  0001 C CNN
F 3 "~" H 6350 2250 50  0001 C CNN
	1    6350 2250
	0    1    1    0   
$EndComp
Connection ~ 6350 1900
Wire Wire Line
	6350 1900 6600 1900
Wire Wire Line
	7350 2850 7350 2700
Connection ~ 6350 2850
Wire Wire Line
	6350 2850 7350 2850
$Comp
L power:GND #PWR08
U 1 1 5E850178
P 6350 3000
F 0 "#PWR08" H 6350 2750 50  0001 C CNN
F 1 "GND" H 6355 2827 50  0000 C CNN
F 2 "" H 6350 3000 50  0001 C CNN
F 3 "" H 6350 3000 50  0001 C CNN
	1    6350 3000
	1    0    0    -1  
$EndComp
Wire Wire Line
	6350 2850 6350 3000
Wire Wire Line
	6000 2100 6200 2100
Wire Wire Line
	6200 2100 6200 2200
Wire Wire Line
	6200 2200 6750 2200
Wire Wire Line
	6350 2400 6350 2850
Wire Wire Line
	6350 1900 6350 2100
Wire Wire Line
	6000 2200 6150 2200
Wire Wire Line
	6150 2200 6150 2300
Wire Wire Line
	6150 2300 6750 2300
$Comp
L Device:C_Small C_Vbus1
U 1 1 5E85372D
P 6350 1700
F 0 "C_Vbus1" H 6442 1746 50  0000 L CNN
F 1 "4.7pf" H 6442 1655 50  0000 L CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" H 6350 1700 50  0001 C CNN
F 3 "~" H 6350 1700 50  0001 C CNN
	1    6350 1700
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR06
U 1 1 5E8537E7
P 6200 1600
F 0 "#PWR06" H 6200 1350 50  0001 C CNN
F 1 "GND" H 6205 1427 50  0000 C CNN
F 2 "" H 6200 1600 50  0001 C CNN
F 3 "" H 6200 1600 50  0001 C CNN
	1    6200 1600
	1    0    0    -1  
$EndComp
Wire Wire Line
	6350 1800 6350 1900
Wire Wire Line
	6200 1600 6350 1600
Wire Wire Line
	7950 1500 8100 1500
Wire Wire Line
	7950 1600 8100 1600
Text GLabel 8100 1500 2    50   Input ~ 0
RX0
Text GLabel 8100 1600 2    50   Input ~ 0
TX0
Wire Wire Line
	4000 3950 4150 3950
Wire Wire Line
	4000 4050 4150 4050
Text GLabel 4100 3950 2    50   Input ~ 0
TX0
Text GLabel 4100 4050 2    50   Input ~ 0
RX0
Wire Wire Line
	7950 1800 8100 1800
Text GLabel 8100 1800 2    50   Input ~ 0
DTR
Wire Wire Line
	2650 1150 2750 1150
Wire Wire Line
	2750 1150 2750 1000
$Comp
L Device:C_Small C_dtr1
U 1 1 5E858966
P 2750 900
F 0 "C_dtr1" H 2842 946 50  0000 L CNN
F 1 "100Nf" H 2842 855 50  0000 L CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" H 2750 900 50  0001 C CNN
F 3 "~" H 2750 900 50  0001 C CNN
	1    2750 900 
	1    0    0    -1  
$EndComp
Wire Wire Line
	2750 800  2750 700 
Text GLabel 2750 700  2    50   Input ~ 0
DTR
Connection ~ 3500 700 
Wire Wire Line
	3500 700  3500 950 
Wire Wire Line
	7450 2700 7450 2850
Wire Wire Line
	7450 2850 7350 2850
Connection ~ 7350 2850
$Comp
L Device:C_Small C_CP1
U 1 1 5E85D9B1
P 7250 700
F 0 "C_CP1" H 7158 654 50  0000 R CNN
F 1 "100nF" H 7158 745 50  0000 R CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" H 7250 700 50  0001 C CNN
F 3 "~" H 7250 700 50  0001 C CNN
	1    7250 700 
	-1   0    0    1   
$EndComp
$Comp
L power:GND #PWR010
U 1 1 5E85DABA
P 7050 650
F 0 "#PWR010" H 7050 400 50  0001 C CNN
F 1 "GND" H 7055 477 50  0000 C CNN
F 2 "" H 7050 650 50  0001 C CNN
F 3 "" H 7050 650 50  0001 C CNN
	1    7050 650 
	1    0    0    -1  
$EndComp
Wire Wire Line
	7250 900  7250 800 
Wire Wire Line
	7050 650  7050 600 
Wire Wire Line
	7050 600  7250 600 
Wire Wire Line
	6750 1800 6600 1800
Wire Wire Line
	6600 1800 6600 1900
Connection ~ 6600 1900
Text GLabel 6000 1900 0    50   Input ~ 0
VBUS
Text GLabel 6000 2100 0    50   Input ~ 0
D+
Text GLabel 6000 2200 0    50   Input ~ 0
D-
$Comp
L BoardLayout:SQX_MOD U2
U 1 1 5E87B20B
P 7300 4600
F 0 "U2" H 7300 5000 50  0000 L CNN
F 1 "SQX_MOD" H 7150 4000 50  0000 L CNN
F 2 "SQX_MOD:SQX_MOD_SMD" H 6500 4050 50  0001 C CNN
F 3 "" H 6500 4050 50  0001 C CNN
	1    7300 4600
	1    0    0    -1  
$EndComp
Wire Wire Line
	4000 1250 4100 1250
Wire Wire Line
	4000 1350 4100 1350
Wire Wire Line
	4000 1450 4100 1450
Wire Wire Line
	4000 1550 4100 1550
Wire Wire Line
	4000 1650 4100 1650
Wire Wire Line
	4000 1750 4100 1750
Wire Wire Line
	4000 1850 4100 1850
Wire Wire Line
	4000 1950 4100 1950
Wire Wire Line
	4000 2150 4100 2150
Wire Wire Line
	4000 2250 4100 2250
Wire Wire Line
	4000 2350 4100 2350
Wire Wire Line
	4000 2450 4100 2450
Wire Wire Line
	4000 2550 4100 2550
Wire Wire Line
	4000 2650 4100 2650
Wire Wire Line
	4000 2750 4100 2750
Wire Wire Line
	4000 2850 4100 2850
Wire Wire Line
	4000 3050 4100 3050
Wire Wire Line
	4000 3150 4100 3150
Wire Wire Line
	4000 3250 4100 3250
Wire Wire Line
	4000 3350 4100 3350
Wire Wire Line
	4000 3450 4100 3450
Wire Wire Line
	4000 3550 4100 3550
Wire Wire Line
	4000 3650 4100 3650
Wire Wire Line
	4000 3750 4100 3750
Wire Wire Line
	4000 4150 4100 4150
Wire Wire Line
	4000 4250 4100 4250
Wire Wire Line
	4000 4350 4100 4350
Wire Wire Line
	4000 4450 4100 4450
Wire Wire Line
	4000 4550 4100 4550
Wire Wire Line
	4000 4650 4100 4650
Text GLabel 4100 1250 2    50   Input ~ 0
PA0
Text GLabel 4100 1350 2    50   Input ~ 0
PA1
Text GLabel 4100 1450 2    50   Input ~ 0
PA2
Text GLabel 4100 1550 2    50   Input ~ 0
PA3
Text GLabel 4100 1650 2    50   Input ~ 0
PA4
Text GLabel 4100 1750 2    50   Input ~ 0
PA5
Text GLabel 4100 1850 2    50   Input ~ 0
PA6
Text GLabel 4100 1950 2    50   Input ~ 0
PA7
Text GLabel 4100 2150 2    50   Input ~ 0
PB0
Text GLabel 4100 2250 2    50   Input ~ 0
PB1
Text GLabel 4100 2350 2    50   Input ~ 0
PB2
Text GLabel 4100 2450 2    50   Input ~ 0
PB3
Text GLabel 4100 2550 2    50   Input ~ 0
PB4
Text GLabel 4100 2650 2    50   Input ~ 0
PB5
Text GLabel 4100 2750 2    50   Input ~ 0
PB6
Text GLabel 4100 2850 2    50   Input ~ 0
PB7
Text GLabel 4100 3050 2    50   Input ~ 0
PC0
Text GLabel 4100 3150 2    50   Input ~ 0
PC1
Text GLabel 4100 3250 2    50   Input ~ 0
PC2
Text GLabel 4100 3350 2    50   Input ~ 0
PC3
Text GLabel 4100 3450 2    50   Input ~ 0
PC4
Text GLabel 4100 3550 2    50   Input ~ 0
PC5
Text GLabel 4100 3650 2    50   Input ~ 0
PC6
Text GLabel 4100 3750 2    50   Input ~ 0
PC7
Text GLabel 4100 4150 2    50   Input ~ 0
PD2
Text GLabel 4100 4250 2    50   Input ~ 0
PD3
Text GLabel 4100 4350 2    50   Input ~ 0
PD4
Text GLabel 4100 4450 2    50   Input ~ 0
PD5
Text GLabel 4100 4550 2    50   Input ~ 0
PD6
Text GLabel 4100 4650 2    50   Input ~ 0
PD7
Wire Wire Line
	8000 4200 8050 4200
Wire Wire Line
	8000 4300 8050 4300
Wire Wire Line
	8000 4400 8050 4400
Wire Wire Line
	8000 4500 8050 4500
Wire Wire Line
	8000 4600 8050 4600
Wire Wire Line
	8000 4700 8050 4700
Wire Wire Line
	8000 4800 8050 4800
Wire Wire Line
	8000 4900 8050 4900
Wire Wire Line
	8000 5000 8050 5000
Wire Wire Line
	8000 5100 8050 5100
Text GLabel 8050 4200 2    50   Input ~ 0
PB4
Text GLabel 8050 4300 2    50   Input ~ 0
PB5
Text GLabel 8050 4800 2    50   Input ~ 0
TX0
Text GLabel 8050 4900 2    50   Input ~ 0
RX0
Text GLabel 8050 4400 2    50   Input ~ 0
PB6
Text GLabel 8050 4500 2    50   Input ~ 0
PB7
Text GLabel 8050 4600 2    50   Input ~ 0
PC0
Text GLabel 8050 4700 2    50   Input ~ 0
PC1
Text GLabel 8050 5000 2    50   Input ~ 0
PD2
Text GLabel 8050 5100 2    50   Input ~ 0
PD3
$Comp
L power:GND #PWR011
U 1 1 5E8C6C73
P 8100 5250
F 0 "#PWR011" H 8100 5000 50  0001 C CNN
F 1 "GND" H 8105 5077 50  0000 C CNN
F 2 "" H 8100 5250 50  0001 C CNN
F 3 "" H 8100 5250 50  0001 C CNN
	1    8100 5250
	1    0    0    -1  
$EndComp
Wire Wire Line
	8100 5200 8100 5250
Wire Wire Line
	8000 5200 8100 5200
Wire Wire Line
	7800 5650 7800 5700
Wire Wire Line
	7700 5650 7700 5700
Wire Wire Line
	7600 5650 7600 5700
Wire Wire Line
	7500 5650 7500 5700
Wire Wire Line
	7400 5650 7400 5700
Wire Wire Line
	7300 5650 7300 5700
Wire Wire Line
	7200 5650 7200 5700
Wire Wire Line
	7100 5650 7100 5700
Wire Wire Line
	7000 5650 7000 5700
Wire Wire Line
	6900 5650 6900 5700
Text GLabel 7800 5700 3    50   Input ~ 0
PA0
Text GLabel 7700 5700 3    50   Input ~ 0
PA1
Text GLabel 7600 5700 3    50   Input ~ 0
PA2
Text GLabel 7500 5700 3    50   Input ~ 0
PA3
Text GLabel 7400 5700 3    50   Input ~ 0
PA4
Text GLabel 7300 5700 3    50   Input ~ 0
PA5
Text GLabel 7200 5700 3    50   Input ~ 0
PA6
Text GLabel 7100 5700 3    50   Input ~ 0
PA7
Text GLabel 7000 5700 3    50   Input ~ 0
PB0
Text GLabel 6900 5700 3    50   Input ~ 0
PB1
$Comp
L power:GND #PWR09
U 1 1 5E8EAE9E
P 6800 5800
F 0 "#PWR09" H 6800 5550 50  0001 C CNN
F 1 "GND" H 6805 5627 50  0000 C CNN
F 2 "" H 6800 5800 50  0001 C CNN
F 3 "" H 6800 5800 50  0001 C CNN
	1    6800 5800
	1    0    0    -1  
$EndComp
Wire Wire Line
	6800 5650 6800 5800
Wire Wire Line
	6600 5200 6550 5200
Wire Wire Line
	6600 5100 6550 5100
Wire Wire Line
	6600 5000 6550 5000
Wire Wire Line
	6600 4900 6550 4900
Wire Wire Line
	6600 4800 6550 4800
Wire Wire Line
	6600 4700 6550 4700
Wire Wire Line
	6600 4600 6550 4600
Wire Wire Line
	6600 4500 6550 4500
Wire Wire Line
	6600 4400 6550 4400
Wire Wire Line
	6600 4300 6550 4300
Text GLabel 6550 5200 0    50   Input ~ 0
PB2
Text GLabel 6550 5100 0    50   Input ~ 0
PB3
Text GLabel 6550 5000 0    50   Input ~ 0
PC2
Text GLabel 6550 4900 0    50   Input ~ 0
PC3
Text GLabel 6550 4800 0    50   Input ~ 0
PC4
Text GLabel 6550 4700 0    50   Input ~ 0
PC5
Text GLabel 6550 4600 0    50   Input ~ 0
PC6
Text GLabel 6550 4500 0    50   Input ~ 0
PC7
Text GLabel 6550 4400 0    50   Input ~ 0
PD4
Text GLabel 6550 4300 0    50   Input ~ 0
RESET
Wire Wire Line
	2650 1250 2550 1250
Connection ~ 2650 1250
Text GLabel 2550 1250 0    50   Input ~ 0
RESET
Wire Wire Line
	6600 4200 6200 4200
Wire Wire Line
	6200 4200 6200 4250
$Comp
L power:GND #PWR07
U 1 1 5E91A6B1
P 6200 4250
F 0 "#PWR07" H 6200 4000 50  0001 C CNN
F 1 "GND" H 6205 4077 50  0000 C CNN
F 2 "" H 6200 4250 50  0001 C CNN
F 3 "" H 6200 4250 50  0001 C CNN
	1    6200 4250
	1    0    0    -1  
$EndComp
Connection ~ 6200 4200
Wire Wire Line
	6900 3700 6900 3650
Wire Wire Line
	7000 3700 7000 3650
Wire Wire Line
	7100 3700 7100 3650
Wire Wire Line
	7200 3700 7200 3650
Wire Wire Line
	7300 3700 7300 3650
Wire Wire Line
	7400 3700 7400 3650
Wire Wire Line
	7500 3700 7500 3650
Wire Wire Line
	7600 3700 7600 3650
Wire Wire Line
	7700 3700 7700 3650
Text GLabel 6900 3650 1    50   Input ~ 0
PD5
Text GLabel 7000 3650 1    50   Input ~ 0
PD6
Text GLabel 7100 3650 1    50   Input ~ 0
PD7
Text GLabel 7200 3650 1    50   Input ~ 0
AREF
Wire Wire Line
	2800 1850 2750 1850
Text GLabel 2750 1850 0    50   Input ~ 0
AREF
Text GLabel 7300 3650 1    50   Input ~ 0
D-
Text GLabel 7400 3650 1    50   Input ~ 0
D+
Text GLabel 7500 3650 1    50   Input ~ 0
VBUS
Text GLabel 7700 3650 1    50   Input ~ 0
VBUS
Wire Wire Line
	3500 700  3600 700 
Text GLabel 3600 700  2    50   Input ~ 0
VBUS
Wire Wire Line
	7800 3700 7800 3350
Wire Wire Line
	7800 3350 6200 3350
Text GLabel 7600 3650 1    50   Input ~ 0
VBUS
$Comp
L Device:Crystal_GND24 Y1
U 1 1 5E8809BC
P 2350 1550
F 0 "Y1" V 2304 1791 50  0000 L CNN
F 1 "Crystal_GND24" V 2395 1791 50  0000 L CNN
F 2 "Crystal:Crystal_SMD_5032-4Pin_5.0x3.2mm" H 2350 1550 50  0001 C CNN
F 3 "~" H 2350 1550 50  0001 C CNN
	1    2350 1550
	0    1    1    0   
$EndComp
Wire Wire Line
	2800 1450 2650 1450
Wire Wire Line
	2650 1450 2650 1400
Wire Wire Line
	2650 1400 2350 1400
Connection ~ 2350 1400
Wire Wire Line
	2350 1400 2150 1400
Wire Wire Line
	1900 1400 1900 1600
Connection ~ 1900 1700
Wire Wire Line
	2800 1650 2650 1650
Wire Wire Line
	2650 1650 2650 1700
Wire Wire Line
	2650 1700 2350 1700
Wire Wire Line
	2350 1700 2150 1700
Connection ~ 2350 1700
Wire Wire Line
	1950 1700 1900 1700
Wire Wire Line
	2550 1550 2550 1600
Wire Wire Line
	2550 1600 1900 1600
Connection ~ 1900 1600
Wire Wire Line
	1900 1600 1900 1700
Wire Wire Line
	2150 1550 1600 1550
Wire Wire Line
	1600 1550 1600 1500
Text GLabel 1600 1500 0    50   Input ~ 0
VBUS
Wire Wire Line
	6200 3350 6200 4200
$EndSCHEMATC
