# Diy-Radio-telescope
NOTE: This project is currently in its design phase. No physical prototype has been made yet.  
A radio telescope mounted on an two axis alt-azimuth motorized mount for observing radio phenomenon.  
# Overview 
The Radio telescope will be made up of two systems.  
- Esp32 powered dual axis mount  
 (An Esp32 will control two stepper motors which will motorize two axes of the mount. The mount will move in a raster scan pattern across the sky.)
- Radio reciever  
  (An parabolic satallite ~75cm in diameter dish will will feed signal into a Low Noise Amplifier which goes through a Software Defined Radio dongle into a computer where it will be processed and converten into a 2d image map)  
# Planned components
- Mount  
  1.Esp32
  2.Stepper motor 2x(NEMA17)  
  3.Stepper motor driver board 2x(DRV8825)  
  4.MPU9250 Gyroscope board  
  5.BreadBoard and wires for easy wiring 
- Radio reciever  
  1.A Antenna  
  2.A Low noise amplifier  
  3.A Software defined radio dongle (RTL-SDR)  
  4.A computer  
  5.SMA connectors.
# Bill of Materials
Heres everything you need for this project. [Bill Of Materials](BOM.csv)  
# CAD  
The Basic Cad design Assembly Of the mount can be found at [CAD Radio Telescope](<Radio Telescope.step>)
<img width="1920" height="1080" alt="CAD Assembly" src="https://github.com/user-attachments/assets/61eeb32e-ff1f-426d-9cc0-bc1dd4e0e6fb" />
The Mount utilizes Gears to increase torque.
<img width="1920" height="1080" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/1b288a7f-7db5-4c8e-81af-5256dfdb4b58" />





