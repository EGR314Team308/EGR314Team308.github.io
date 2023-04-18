<h1>Component Selection</h1>
These components are mostly set in stone. Each person in the group is free to choose another component as long as it is represented in the current documents. As the team sees it, this portion of the project is complete, because all persons on the team have made individual schematics and combined them into the hardware proposal, which you may direct to or ask about.
<br><br>




Component Selection
Marla Hawthorne, Andrew Sarrasin, Lina Mayyas, Jeffrey Davis
Arizona State University 
EGR 314, Team 308
Professor Travis Kelley


Introduction	2
Major components	2
Op Amp -	2
Anemometer	4
Analog to digital converter (ADC)	6
Switching Voltage Regulator	8
Motor Driver	10


Introduction
This document serves as the showcase of our component selection process. The team was required to select the best components for the tasks that needed to be performed. The components in question being an operational amplifier (op amp), anemometer, analog to digital converter (ADC), switching voltage regulator, and motor driver. While researching the requirements for each component, the three most promising components were entered into the charts below. After careful consideration the best one was picked from those three.
Major components
Op Amp - 
Solution
Pros
Cons

Surface mount is in line with class requirements
General purpose so we can potentially use it for other things
Range of acceptable voltage already includes 3.3V
Relatively low temperature range (hard to solder)


BD1321G-TR
0.69/ each
https://www.digikey.com/en/products/detail/rohm-semiconductor/BD1321G-TR/5720856?s=N4IgTCBcDaIEIBECMBmMSDiBaAKgJRAF0BfIA




Solution
Pros
Cons

Has an extremely large voltage range (2.7-36V)
Durable in extreme temperature and moisture.
Does not require much supply current
Can only be bought in bulk (100+)
2156-OPA234E-ND
$1 /each
https://www.digikey.com/en/products/detail/rochester-electronics-llc/OPA234E/12602361


Solution
Pros
Cons

Zero-Drift OpAmp minimizes input offset voltage.
Durable in extreme temperature and moisture.
Price is much higher than other available OpAmps
505-AD8630ARZ-ND




$9.21 /each




https://www.digikey.com/en/products/detail/analog-devices-inc/AD8630ARZ/998043



Choice: BD1321G-TR
Rationale: Our team chose this OpAmp because it meets class requirements and is able to be surface mounted, it is a general person OpAmp which means our team could use it for multiple subsystems, and it meets the acceptable voltage range required for our design. 
Anemometer
Solution
Pros
Cons

Relatively easy to use


Expensive
Needs an extra part to research
1528-1328-ND
44.95
https://www.digikey.com/en/products/detail/adafruit-industries-llc/1733/5356813?utm_adgroup=Sensors%20%26%20Transducers&utm_source=google&utm_medium=cpc&utm_campaign=Dynamic%20Search_EN_Product&utm_term=&utm_content=Sensors%20%26%20Transducers&gclid=CjwKCAiAleOeBhBdEiwAfgmXf8sIo39AlE1VwRqEgjujfe8mDJ45h0yy2RzGvRM1hHp4qsWh1zrcuRoC4A4QAvD_BwE


Solution
Pros
Cons
 
Cheap
Runs in a voltage range from 2.7 to 5V.
Simple voltage change output.
Will require external wiring.
Will not work with stepper-specific motor drivers.
505-AD8630ARZ-ND
$3.86 /each
https://www.digikey.com/en/products/detail/analog-devices-inc/AD8630ARZ/998043


Solution
Pros
Cons

Product has a digital output
Small enough to fit in a compact design
Datasheet has a typical voltage curve already
Cannot sense direction on its own
Through hole mounting
Most likely inaccurate
3567-PAV1015-ND
$49.00
https://www.digikey.com/en/products/detail/posifa-technologies/PAV1015/14122017?s=N4IgTCBcDaIIIDsCmBbA9ipAXJAnEAugL5A


Choice: 505-AD8630ARZ-ND Motor
Rational: We chose this component as it is the most realistic for this type of project. Using a motor as an anemometer is cheap and simple with a constructed wind cup. As an input, the microcontroller can use the voltage changes produced by the motor’s rotation.
Analog to digital converter (ADC)
Solution
Pros
Cons

Product has 4 inputs and 4 outputs
Has a supply input range (3-5V)
Uses SPI
Extremely moisture sensitive
584-AD7858ARZ 




$29.15 /each




https://www.mouser.com/ProductDetail/Analog-Devices/AD7858ARZ?qs=%2FtpEQrCGXCztvdsnhNDaIw%3D%3D


Solution
Pros
Cons

Can withstand extreme temperature
Has a supply input range (3-5V)
Considered a “High Speed” ADC
Uses SPI
Has only one output channel
595-ADS8924BRGET 




$13.22




https://www.mouser.com/ProductDetail/Texas-Instruments/ADS8924BRGET?qs=osPbIpHqQ9VG6i7AYocAxg%3D%3D




Solution
Pros
Cons

10 bit
Extremely small
3-5.5 V input voltage
Single-ended input limits output to voltage differentials.
595-TLV1543CDW




$8.88 /each




https://www.mouser.com/ProductDetail/Texas-Instruments/TLV1543CDW?qs=3FVjRv9mUZ8lif0mcM%252BeQg%3D%3D


Choice: 595-ADS8924BRGET
Rational: Due to the moisture sensitivity the first option is unrealistic; another subsystem is meant to detect moisture. The single output can be worked with since the component is small and the pcb would only need to fit two or three. The only other physical contradiction to the choice would be soldering difficulty. 
Switching Voltage Regulator
Solution
Pros
Cons

Fits most of our criteria
Max Input Voltage is 1.8 V
Higher Cost 
LTC1502CS8-3.3#PBF




$3.42




https://www.digikey.com/en/products/detail/rochester-electronics-llc/LTC1502CS8-3-3-PBF/13496260


Solution
Pros
Cons

Input Voltage max of 35V 
Cheap
Output Voltage Minimum of 5V
Would not output 3.3 easily 
MC7805BDTG




$0.67




https://www.digikey.com/en/products/detail/onsemi/MC7805BDTG/1481212?utm_adgroup=Integrated%20Circuits%20%28ICs%29&utm_source=google&utm_medium=cpc&utm_campaign=Shopping_Supplier_ON%20Semiconductor_0488_Co-op&utm_term=&utm_content=Integrated%20Circuits%20%28ICs%29&gclid=EAIaIQobChMIu47d_q71_AIV79uGCh1_NQgLEAQYASABEgIJd_D_BwE


Solution
Pros
Cons

Cheapest option  
Requires an amplifier due to it only outputting 3.1V
MCP1700T-3102E/TT




$0.5




https://www.mouser.com/ProductDetail/Microchip-Technology-Atmel/MCP1700T-3102E-TT?qs=uHi2%2FQoPa5DCdC3guxdHbw%3D%3D&mgh=1&gclid=EAIaIQobChMIu47d_q71_AIV79uGCh1_NQgLEAQYCCABEgIR-_D_BwE


Choice: MCP1700T-3102E/TT
Rational: The team chose this regulator to simplify what we have to do to meet the requirements. It was fairly difficult to find a regulator that accepts 9 volts and outputs a fixed 3.3 volts. Amplifying the output voltage would be simpler than regulating it or decreasing the input voltage by 8V. 
Motor Driver
Solution
Pros
Cons

Cleared by graders
Available in Peralta
5-36 V input voltage
5V input conflicts with 3.3V input of many other components
IFX9201SGAUMA1




$4.88 /each




https://www.digikey.com/en/products/detail/infineon-technologies/IFX9201SGAUMA1/5415542


Solution
Pros
Cons

Specifically notes use with PWM pins on microcontrollers
Works with selected motor

3-3.6 V input voltage
6 week lead time
EMC2301-1-ACZL-TR




$1.24 /each




https://www.digikey.com/en/products/detail/microchip-technology/EMC2301-1-ACZL-TR/3872090


Solution
Pros
Cons

16 pin
PWM based
Can be obtained in 4 weeks

3-3.6 V input voltage
EMC2305-1-AP-TR




$2.46 /each




https://www.digikey.com/en/products/detail/microchip-technology/EMC2305-1-AP-TR/3872093


Choice: IFX9201SGAUMA1
Rationale: Our team chose this motor driver as we already have access to it through the adjacent storage room. Minimal soldering will be needed to implement it in a given circuit. Also, the component’s functionality will necessitate a voltage regulator, which is included as a subsystem. This motor driver should be able to relay the PWM signal from the microcontroller with minimal effort.




**Power Budget:**
<br><br>
![Pro](PowerBudget.jpg)
<br>

This is the power budget for all of our main components It shows our device is to run for 160 hours on a 9 volt battery. Meaning we have about a week of runtime.
