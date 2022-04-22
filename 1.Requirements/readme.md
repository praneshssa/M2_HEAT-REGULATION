REQUIREMENTS:

 Components used:

   ATmega328 microcontroller 
   Potentiometer
   Switches
   LED 
   LCD diplay

 Software used:

  SimulIDE
  code block
  GCC Compiler for AVR
  
  Features:

  The System will be able to tell whether a person is seated or not.A person once seated gets the   access to turn ON the heater.
  The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller.


 Strengths, Weakness, Oppurtunities and Threats:

  *Strengths
  *Robust in nature 
  *low cost
  *Easyily accessible by the any person
  *High efficiency

drawbacks:

  This system can be used at low to moderate temperature and also the system cannot be used for very high temperature.

 Detail Requirements:

  High Level Requirements
  ID  Description 
  HLR1  Microcontroller unit    
  HLR2  Switches 
  HLR3  Temperature sensor 
  HLR4  Heater 
  HLR5  Display CDD CRO 

  Low Level Requirements:

  ID  Description HLR ID 
  LLR1  ATMega328   HLR1 
  LLR2  ADC and Potentiometer HLR3
  LLR3  Thermo electric module  HLR4 
  LLR4  LCD and LED, PWM  HLR5 


