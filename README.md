# BMS345
Protection and charging module for 3/4/5S lithium batteries 
This project is fully open-source and may be used commercially.
ZOUDIO is only liable for products of its own production.

![Picture of the BMS345](BMS345%20picture.jpg)

Based on:
Texas Instruments BQ77915 primary battery protector
Texas Instruments BQ24650 battery charger

Configuration is set by using the onboard header. 

Specifications (for more details and instructions, refer to the PDF datasheet)
-	Overvoltage:				4.2V ±10mV, delay 1S
-	Undervoltage: 			2.9V ±18mV, delay 1S
-	Cell balancing 			4mA per cell
-	Maximum continuous discharge:	10A
-	Overcurrent protection: 		15A, delay 180mS
-	Short-circuit protection: 		30A, delay 1mS
-	Recovery after fault event: 		Attach charger
-	Open cell/wire detection:		4.5S delay
-	Power consumption: 			8μA typical
-	Charging current:			1A
-	Charging voltage:			4.05V per cell
-	MPPT voltage:			17.5V
-	Operating temperature: 		-40 to 85 °C
-	Dimensions (WxHxD):		71x38x15mm
