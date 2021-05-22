# SIT210_PCB_Files
SIT210 10.1HD

My PCB design is purposefully simple. I designed my embedded system to achieve my goal as simply as possible. 

My PCB conforms to the Feather Standards. The overall size is correct, and the rounded corners fit with the aesthetics of the Particle Boron. The mounting holes conform to the standard, allowing for the use of cases later on in the design process. 

The headers allow the Particle Boron to be easily attached. There are free solder points for the I2C LCD display, which will be used to communicate with the user.

There is a dedicated space for the Neo 7M GPS module I am using. This will require the purchase and soldering of 90 degree female headers. This will allow the GPS unit to lie flat along the length of the Particle Boron. 

The electrical runs are done over 2 layers, allowing power and ground to be shared amongst the components. 

The design conforms to the PCB Design Rule Checks suggested by Easy EDA.
