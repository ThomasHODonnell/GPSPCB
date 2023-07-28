

# GPS PCB - designing a consumer electronic from start to finish


## *Concepts*
- My father run a bicycle shop. Some of his customers' bicycles have been stolen. He asked me if I could design a product to help combat this problem. This problem led me to a GPS based solution - to get things started. 
- The solution provided here is an embedded system that can transmit its location upon request utilizing a satallite HTTP request API.
- This product combats the problem by not only locating a stolen / lost bicycle, but my locating a potential thief. Therefore, this product can act as a form of location verification for law enforcement bodies in pursuit of any item this PCB is attached to. 

## *Logistics* 
- I have designed 3D printed CAD models to safely secure this system on a moving bicycle. This system comfortably holds the PCB, its components and a battery. 
- While I have not completed suffient testing to determine the battery life of this system, its power consumption is very low for a reasonably sized battery and its capacity. This combination should ensure that the device does not need to be recharged for a reasonable amount of time. 

## Technical Information
- This initial design is intended to be minimalistic. I have foregone a Microcontroller Unit in an effort to minimize power consumption, size, and cost. Alternativly, I have implemented a standalone Reciever / Transciever combination to complete the necessary funcitonality without any additional computing. 
- Of course, there are a number of other ICs to accompany these functional components, such as LDO Regulators, Operational Amplifiers, Logic Gates, Switches, Battery IC, Low Noise Amplifier, and Antennas.  
- While this Electronic Circuit requires significantly more testing, the technical aspectrs of this solution offer a helpful initial solution to a logicically challenging problem. 

## Disclaimer
- I am a third-year Computer Engineering Student. In no fashion am I qualified to develop professional grade products at this point in my career. 
- Therefore, I would not recommend using any of my design choices for other applications without inquiring a professional. 
- I will post other README files within other folders with other information, screenshots, and files. 