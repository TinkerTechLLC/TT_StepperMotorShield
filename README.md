# TT_StepperMotorShield
This stepper motor shield is capable of smooth, simultaneous control of two bi-polar stepper using [Allegro A4988 
stepper driver breakout sticks](https://www.pololu.com/product/1182). It also has a handy mounting location for an 
[XBee radio adapter board](https://www.adafruit.com/products/126). Use caution when using the XBee radio at the 
same time as the motors. It has been found to cause hiccups in the motors step interrupts, so this can cause the motors
to stall when running at higher speeds.

Order boards here: https://oshpark.com/shared_projects/M8zwapGA

Library for controller shield via Arduino Uno: https://github.com/TinkerTechLLC/TT_StepperMotorShield_Library
