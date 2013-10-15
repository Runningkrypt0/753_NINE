753_NINE
========

This repo contains code for FIRST team 753's 2011 robot: NINE.

Language:
  Labview (FRC 2013 Edition)

  The structure for some branches will be similar in structure to the default robot code given by FIRST. However 
others may differ or contain code that has been optimized for the specific usage. Some code may bypass standard 
libraries or recommended VIs to directly interact with the FPGA. Please use all code in this repo at your own 
discretion and risk. (Writing to the FPGA directly incorrectly or in an unsuitable manner may cause minor to
serious issues with your C-RIO.)

CRIO firmware image: 47

CRIO model: 9074 (8-slot)

Modules: DIO 1

Descrition of contents:
    Autonomous Independent    default sample code for autonomous movements
    Begin                     initializes PWM motor channel refrences and Joystick refrences
    Disabled                  idle code to prevent unwarrented behavior
    Elapsed Times             default code for timing (its a clock)
    Finish                    closes refrences
    .aliases                  device refrences
    .lvps                     project settings
    .lvproj                   main project file
    Periodic tasks            repetitive timing based tasks
    Robot Global Data         global variable container
    Robot Main                main code file
    Teleop                    remote operater code and control
    Test                      used for safely testing sensors/actuators
    Vision Processing         Handles camera data and image analysis (regardless of their being no other camera code)
