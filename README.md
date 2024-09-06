# Inductive-Proximity-sensor-
Inductive Proximity Sensor capable of detecting Metal objects  
Aim : To design and implement inductive proximity sensor  

-  The inductive sensor works on the principle of Faraday's Law and Lenz's Law. according to Faraday when the current passes through the conductor the electromagnatic field is created (current Passed to coil) and according to Lenz's law the metal object p;aced in magnetic field will produce small currebt called eddy current, this eddy current further produce electric filed whic opposes the filed produced by the coil. with respect to this trigger circuit is designed to idicate preasence and absence of the metal object.   

![image](https://github.com/user-attachments/assets/77fed229-2c08-488a-82ff-f8525f7f83e8)   

# 1 Hardware requirements:  

 1.1 IC - uA741  
 -  The uA741 is a widely used operational amplifier (op-amp) IC, it has a high gain-bandwidth product of 1 MHz, the IC has a high input impedance of 2 MΩ and has a low output impedance of 75 Ω. The uA741 can operate on a single supply voltage of 5 to15 V, it can drive loads up to 10 mA.  

  
![image](https://github.com/user-attachments/assets/db8cf406-efc2-4e6c-9fbc-45085ec70aaf)  

1.2 LED  
-  LED stands for Light Emitting Diode, they are semiconductor devices that emit light. They work by passing a current through a p-n junction, used to idicate the presence and absence of the metal object
  
![image](https://github.com/user-attachments/assets/cf725d9e-29cc-41b2-b846-b5b945aca1fb)  

1.3 Resister  
- A resistor is a passive electronic component that opposes the flow of current, they are used to control voltage and current levels in a circuit.  

![image](https://github.com/user-attachments/assets/7725692b-afc6-4dc4-9da2-ca9c7fa87cb8)  

1.4 Capacitor  
-  A capacitor is a passive electronic component that stores energy in an electric field.
  
![image](https://github.com/user-attachments/assets/d0b8bf9b-3ced-43e4-95e0-02ad2fccdf55)  


# 2 Methodology :  

2.1 Colpitts Oscillator Circuit  
- A Colpitts oscillator is a type of LC oscillator circuit that uses an LC resonant tank circuit (inductor L and capacitor C) to generate sinusoidal oscillations where feedback is derived form a capacitive divider. which is connected to the coil to prodece magnetic field (1.4 Mhz frequcey is generated).
  
![image](https://github.com/user-attachments/assets/cc71c562-8d98-4108-a42f-c7963789b94c)  

2.2 Coil  
- Coils, play a crucial role in generating and interacting with magnetic fields. When current flows through a coil, a magnetic field is generated around it according to Ampère's circuital law. The strength of this magnetic field is directly proportional to the current passing through the coil.  

![image](https://github.com/user-attachments/assets/57989b5c-8e34-4bfb-9087-004b6d87f1d9)  

2.3 Trigger Circuit  
The Schmitt trigger circuit is a type of comparator circuit, it uses positive feedback to implement hysteresis. The circuit has two thresholds called upper threshold point (UTP) and lower threshold point (LTP). Connected to LED to indicate the trigger.  

![image](https://github.com/user-attachments/assets/9701e251-2ff9-4d56-a699-16fc866fec14)  


# 3 Result :  

3.1 Output of Colpitts oscillator circuit  
- The oscillator circuit was designed for the production of 1.41 MHz frequency but practically it was able to generate frequency ranges from 1.24 MHz to 1.6 MHz.
  
![image](https://github.com/user-attachments/assets/7d6e3651-6e30-4dc8-98a6-77dba18fc90b)  

3.2 Magnitic field test using magnet  
- Magent is placed between the coil, when the current is not passed to the coil then there is no diflection of magnet but the current is passed then there is a difflection of coil indicating that coil has produced magneticfiled.

    
![image](https://github.com/user-attachments/assets/cc02ac1e-2468-46fb-a6d7-f0c99b31df65)  

3.3 Output when the absence and presence of metal object  
- When the sensor is turned ON and metal object is not in the filed of coil then the LED is turned ON indicating that the sensor is in ON state and absence of metal object, when the metal is placed in the field of the coil the LED will turn OFF indicating that there is a presece of metal object.
    

![WhatsApp Image 2024-09-06 at 23 43 56_d9bd3e0e](https://github.com/user-attachments/assets/8f23b89b-e4f4-42b7-9cf6-998318d82c60)  


