# Diy-Radio-telescope
NOTE: This project is currently in its design phase. No physical prototype has been made yet.  
A radio telescope mounted on an two axis alt-azimuth motorized mount for observing radio phenomenon.  
# Overview 
The Radio telescope will be made up of two systems.  
- Arduino powered dual axis mount  
 (An arduino will control two stepper motors which will motorize two axes of a tripod. The mount will move in a raster scan pattern across the sky.)
- Radio reciever  
  (An parabolic satallite ~75cm in diameter dish will will feed signal into a Low Noise Amplifier which goes through a Software Defined Radio dongle into a computer where it will be processed and converten into a 2d image map)  
# Planned components
- Mount  
  1.Arduino Uno  
  2.Stepper motor 2x  
  3.Stepper motor driver board 2x  
  4.MPU6050 Gyroscope board  
  5.A cheap tripod  
- Radio reciever  
  1.A Antenna  
  2.A Low noise amplifier  
  3.A Software defined radio dongle capable of 1420.405 Mhz (Hydrogen line) 
  4.A computer 


